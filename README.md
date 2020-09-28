12 factors applications:
#1.Code Base (git)
#2.Dependencies (управление зависимостями)
#3.Config (Enviroment configuration) [Logrus/zap]
#4.Backing Services (работа с сервисами)
#5.Build, release, run (фазы работы с приложениями)[curl -i http://127.0.0.1:8080]
#6.Processes (stateless - пишем в БД сразу, statefull - пишем в БД периодически) 
#7.Port binding - привязка портов
#8.Concurrency (Масштабирование сервисов как отдельных процессов)
#9.Disposability (Утилизируемость) $> ps ax | grep main #process
#10.Dev/prod parity
#11.Logs a)приложение занимается только открытой log-ов в стандартный вывод
         б)приложение не должно заниматься роутингом
         в)приложение не должно хринить log-и как файлы
#12.Admin processes
