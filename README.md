# 12.2_K8S_base_Aleksander_Molokov

### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Ответ

1. Манифест Pod - ![Манифест](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/blob/9c40094eba0a20e7ab51afa08e33168a88248e45/1_pod_hello_world.yaml)

2. Подключение к Pod
   
![1 1 curl pod](https://github.com/ALEMOLOKOV/12.2_K8S_base_Aleksander_Molokov/assets/109212419/bb07dbcc-1313-49ac-a481-0b37e61bc303)

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

## Ответ



