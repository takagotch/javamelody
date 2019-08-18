### javamelody
---
https://github.com/javamelody/javamelody

```java
// javamelody-core/src/test/java/net/bull/javamelody/TestMonitoringSpringInterceptor.java

public class TestMonitoringSprintInterceptor {
  private static final String TEST_CONTEXT_FILENAME = "sprint-context.xml";
  private static final String MONITORING_CONTEXT_FILENAME = "net/bull/javamelody/monitoring-spring.xml";
  private static final String MONITORING_CONTEXT_FILENAME = "net/bull/javamelody/monitoring-spring-scheduled.xml";
  private static final String REQUESTS_COUNT = "requestsCount";
  
  private ConfigurableApplicationContext context;
  
  @Before
  public void setUp() {
    Utils.initialize();
    this.context = new ClassPathXmlApplicationContext(
      new String[] { MONITORING_CONTEXT_FILENAME, MONITORING_CONTEXT_FILENAME2,
        TEST_CONTEXT_FILENAME, });
  }
  
  
}

```

```
```

```
```


