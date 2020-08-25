# Nacos
服务读取对应空间的内容作为application.yml ，并将自己的服务交给nacos治理。
重点，nacos的配置 一定要和服务的bootstrap.yml 文件内容保持一致。文件的扩展名 可以为 yaml，也可以为yml。
此时这个服务是作为服务提供方的。
消费者在Nacos Customer 项目里面
