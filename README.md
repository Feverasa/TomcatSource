# TomcatSource
深入剖析tomcat源码




              DefaultListableBeanFactory bf = new DefaultListableBeanFactory();
            new XmlBeanDefinitionReader(bf).loadBeanDefinitions(MAP_CONTEXT);
            Object simpleMap = bf.getBean("simpleMap");
            assertTrue(simpleMap instanceof Map);
            assertTrue(simpleMap instanceof HashMap);
