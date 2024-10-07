Progetto spring boot microservizi con SpringCloud, API Gateway, Load Balancer, Gradle
Nel progetto ci sono un eureka-Server, un ApiGateway e 2 eureka-client di cui uno a tre istanze cosi il ApiGateway con il suo 
LoadBalancer suddivide il carico in modo automatico(si può personalizzare)

eureka-Server = tipo: eureka-server
eureka-client = tipo: eureka-client
api-gateway = tipo: eureka-client

gestite routes personalizzate in api-gateway 
api-gateway di tipo: webflux(richieste assincrone, programmazione reativa )
gestite le 3 istanze di un eureka-client con differenti id nel file: application.properties del eureca-client mutliplicato
