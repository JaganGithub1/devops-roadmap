| Цель и что нужно для изучения + Задания | Как поймем что цель достигнута? | Примерная дата окончания изучения | Aider | Polina
|-|-|-|-|-
| Linux - ядро операционной системы, например Ubuntu построена на базе Linux. Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYuE4z-3BgLYGkZrs-cF4Tep и сделать все задания https://github.com/eabykov/devops-linux | Может устанавливать программы, знает основные команды и может их применять, что такое ядро linux, знает основные папки есть в `/`, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/linux и https://github.com/bregman-arie/devops-exercises#operating-system---self-assessment | 01.03.2023 | [x] | 
| Linux скрипты - простые сценарии, автоматизация рутинных задач. Сделать скрипты для всех заданий https://github.com/eabykov/devops-linux и https://github.com/bregman-arie/devops-exercises/tree/master/topics/shell задания 2,5,9 | Умеет задавать переменные и использовать их, может применять условный оператор IF и использовать CASE, умеет использовать циклы, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/shell | 01.03.2023 | [x] | 
| Git - система управления версиями для совместной работы над проектом и в случае чего откату на старую версию. Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYstwxTEOU05E0URTHnbtA0l до 15 урока и создать свой репозиторий на github с несколькими ветками и тегами | Знает что такое commit и как его делать, умеет делать branch и tag, знает что такое merge и как исправлять конфликты, знает как откатиться на предидущий commit, как склонировать репозиторий локально и как загрузить свои изменения в github, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/git | 01.03.2023 | [x] | 
| Docker - упаковка приложения в image в котором будет все что нужно для запуска. Пройти курс https://github.com/eabykov/devops-docker и посмотреть примеры compose https://github.com/docker/awesome-compose | Понимает зачем нужен docker, умеет создавать свой образ и пушить его в dockerhub, умеет запускать несколько образов вместе используя compose, вопросы https://habr.com/ru/company/southbridge/blog/528206/ | 15.03.2023 | [x] | 
| CI/CD, выполнение автоматически действий по триггеру (например commit, merge, etc.) или расписанию. В курсе https://www.youtube.com/watch?list=PLg5SS_4L6LYstwxTEOU05E0URTHnbtA0l 15й и 16й, https://youtu.be/tE3u1LquFcg?t=212 скорость 1.25, https://github.com/gitlabhq/gitlabhq/blob/master/doc/ci/docker/using_kaniko.md `.gitlab-ci.yml` как собирать Docker Image в GitLab правильно | Сделал автоматическую сборку своего Docker Image и отправку dockerhub хранилище образов (registry) , GitLab CI/CD основные понятия, из каких шагов состоит идеальный пайплайн, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/cicd | 15.03.2023 | [x] |
| Мониторинг - сбор исторических данных о нашей системе https://youtu.be/wDan20_WyNg использовать пример https://github.com/ruanbekker/docker-monitoring-stack-gpnc , Linux серверах, показателей приложений и их логов, сетевых метрик, оповещение если что-то пошло не так. Prometheus + Grafana + metric-server, ELK стек https://youtu.be/ZcC3BTChCY0?t=110 и https://github.com/docker/awesome-compose/tree/master/elasticsearch-logstash-kibana , Трейсинг https://youtu.be/7Dyf4AiUAcQ | Понимает как создавать алерты (оповещения), может настроить мониторинг Docker, linux host и Kubernetes с приложениями в нем (после изучения Kubernetes), вопросы https://github.com/bregman-arie/devops-exercises#prometheus , https://github.com/bregman-arie/devops-exercises#monitoring и https://github.com/bregman-arie/devops-exercises#elastic | 01.04.2023 | |
| Сети, сетевые технологии - как попасть в консоль удаленного сервера, как у нас идет трафик в интернете и тд. Прочесть статью https://habr.com/ru/post/326574/ , https://ru.wikipedia.org/wiki/Маска_подсети и https://habr.com/ru/post/711578/ | SSH, что такое 'пакет', знает уровни TCP/IP, что такое DNS, что такое HTTP протокол и REST, что такое IP и маска подсети, как на linux посмотреть сетевые интерфейсы, сниффинг трафика, что такое Nginx (как выглядит конфиг) и балансировка, вопросы https://github.com/bregman-arie/devops-exercises#network и https://github.com/bregman-arie/devops-exercises/tree/master/topics/dns | 01.04.2023 | | 
| Ansible. Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYufspdPupdynbMQTBnZd31N 1,6,10,12 | Понимает зачем нужен Ansible, что такое идемпотентность, что такое playbook, умеет писать свои роли, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/ansible | 15.04.2023 | | 
| Terraform. Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYujWDTYb-Zbofdl44Jxb2l8 до 17 | Понимает зачем нужен Terraform, знает как создавать ресурсы (например виртуальную машину), где хранится состояние (информация) о том что сделал terraform, вопросы https://habr.com/ru/company/southbridge/blog/528206/ | 15.04.2023 | | 
| Kubernetes - приводит состояние кластера из пункта А в пункт С, нужно только обьяснить с помощью yaml манифестов чего хотим в пункте С. Пройти курс https://www.youtube.com/watch?list=PLg5SS_4L6LYvN1RqaVesof8KAf-02fJSi и https://github.com/eabykov/kubernetes запускать локально через Docker Desktop и поставить linkerd | Понимает зачем нужен Kubernetes, как устанавливать приложения через helm, вопросы https://github.com/bregman-arie/devops-exercises/tree/master/topics/kubernetes | 01.06.2023 | | 

```yaml
- name: Install nginx   # устанавливаем nginx на удаленном сервере
  ansible.builtin.apt:
    name: nginx        # какую программу будет устанавливать (запустит apt install -y nginx)

- name: Copy local nginx config to remote hosts # имя задачи, чтобы мы понимали что делает
  ansible.builtin.copy:
    src: /home/aider/ansible/nginx.conf         # где файл лежит у нас на компе
    dest: /etc/nginx/nginx.conf                 # то куда файл попадет на удаленных хостах
    owner: aider                                # кто будет хозяином файла на удаленной машине
    group: aider                                # какая группа будет у файла на удаленной машине
    mode: u=rw,g=r,o=r                          # какие права будут у файла на удаленной машине

- name: restart nginx # перезапустить nginx
  service:
    name: nginx       # с каким сервисом будем работать
    state: restarted  # перезапустить nginx
    enabled: yes      # запускать nginx при перезапуске системы
```

