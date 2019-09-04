## Варианты, чтобы узнать какое приложение на определенном порту

* `netstat -tap --numeric-ports |grep :<port>`
* `lsof -i tcp:<port>`
