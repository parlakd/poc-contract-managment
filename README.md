# POC - Sözleşme Yönetim Aracı
Satinalma Uzmaninin sözleşme oluşturmaya başladığı ve iş akışını ilerlettikten sonra akışın paralel olarak Satınalma uzmanının Yöneticisine ve Hukuk birimine ilerlediği, Paralel akışdaki herkes tarafından onaylandıktan sonra satınalmaya sözleşme geri gönderilip Arşiv adımınada sonlandırılacak bir akış tasarlanacaktır.

### Gereksinimler

Uygulamayı çalıştırmak için bilgisayarınızda [Docker](https://www.docker.com/) yüklü olmalıdır. Eğer kaynak kodundan uygulamayı derleyip çalıştırmak istiyorsanız bilgisayarınızda [Maven](https://maven.apache.org/) ve [JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) yüklü olmalıdır.

## Kurulum

Kurulum yapıldıktan sonra sistemi [http://localhost:8080/app/tasklist/default/#/login](http://localhost:8080/app/tasklist/default/#/login) adresinden ulaşılabilir. Kullanıcı adı/şifre = ericsson/ericsson

### Varolan Docker Imajını Kullanarak
`docker pull caltuntas/poc-contract-management`


### Kendi Docker Imajını Oluşturarak
`docker-compose build`