# helloworld
after 
1) mvn project 
2)java -jar target\helloworld-1.0.2-shaded.jar server hello-world.yml

I am getting this error:
Caused by: org.glassfish.jersey.server.model.ModelValidationException: Validation of the application resource model has failed during application initialization.
[[FATAL] No injection source found for a parameter of type public com.example.helloworld.api.Saying com.example.helloworld.resources.HelloWorldResource.sayHello(java.util.Optional) at index 0.; source='ResourceMethod{httpMethod=GET, consumedTypes=[], producedTypes=[application/json], suspended=false, suspendTimeout=0, suspendTimeoutUnit=MILLISECONDS, invocable=Invocable{handler=ClassBasedMethodHandler{handlerClass=class com.example.helloworld.resources.HelloWorldResource, handlerConstructors=[org.glassfish.jersey.server.model.HandlerConstructor@6eafb10e]}, definitionMethod=public com.example.helloworld.api.Saying com.example.helloworld.resources.HelloWorldResource.sayHello(java.util.Optional), parameters=[Parameter [type=class java.util.Optional, source=name, defaultValue=null]], responseType=class com.example.helloworld.api.Saying}, nameBindings=[]}']
