# YARA

первое правило

<img width="2542" height="1303" alt="image" src="https://github.com/user-attachments/assets/a3321fda-5215-4e5e-9b43-dc44c654c918" />

    strings:$a=""     указали что надо искать текстовую переменную a
    
    condition:$a       указали что правило выполнилось когда нашли а 

ищем .exe файл 

<img width="2432" height="1253" alt="image" src="https://github.com/user-attachments/assets/7c892889-c78e-4ec8-a5ba-1a228e59d38b" />

    переменная $a={ 4D 5A}  записали бин формат

логика

<img width="2461" height="1250" alt="image" src="https://github.com/user-attachments/assets/05a0e6ff-ce50-4376-ba4d-7aced17387ad" />

поиск в ограниченном пространстве

<img width="1930" height="1183" alt="image" src="https://github.com/user-attachments/assets/605ec05e-9a9d-4a9f-972d-a034f77ee524" />
