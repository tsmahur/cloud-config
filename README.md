# cloud-config

  This ms act as a config ms which will load yml properties from [configurations-server](https://github.com/tsmahur/configurations-server). This is a part of [ms-eureka-gateway-hysrtix-cloud-config](https://github.com/tsmahur/ms-eureka-gateway-hysrtix-cloud-config) Project.
##
### Dependency
    eureka client,  spring-cloud-config-server

### application.yml
    port,app name, uri of git hub, profiles: active: native

### main application class
    @EnableEurekaClient , @EnableConfigServer
