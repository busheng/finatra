java_library(
  name='java',
  dependencies=[
    '3rdparty/jvm/ch/qos/logback:logback-classic',
    '3rdparty/jvm/com/google/inject:guice',
    '3rdparty/jvm/javax/inject:javax.inject',
    'finatra/http',
  ],
  fatal_warnings=False,
  sources=rglobs('*.java'),
  resources=[
    'finatra/examples/java-http-server/src/main/resources'
  ]
)
