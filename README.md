# 12.2_K8S_base_Aleksander_Molokov

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Ответ

1. Манифест Pod hello-world - ![Манифест](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/blob/9c40094eba0a20e7ab51afa08e33168a88248e45/1_pod_hello_world.yaml)

2. Подключение к Pod
   
![1 1 curl pod](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/bb07dbcc-1313-49ac-a481-0b37e61bc303)

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Ответ

1. Pod netology-web ![Манифест](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/blob/1cb7d650cc7afd3508ad65d5d52fab23be25ea94/pod%20netology-web.yaml)

![2 1 pod netology-web](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/140f0045-97a9-414d-989c-eb490a74774b)

2. Service netology-svc ![Манифест](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/blob/ff9774ac82710ab5dd79acef3e147ed6557ae0ef/service%20netology-svc.yaml)

![2 2 svc netology-svc](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/ecda4af6-d43c-48dc-99bf-ba4144002959)

Проверка подключения к Pod netology-web

![2 3 Привязка сервиса к pod](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/3630d339-c2ae-4c45-962b-34de03ae2a43)

3. Подключение к Service netology-svc с помощью port-forward
![curl localhost30080](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/6b833cea-e7be-40af-88d2-e4619c2cac80)




   



