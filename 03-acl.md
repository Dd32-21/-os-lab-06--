<img width="640" height="242" alt="image" src="https://github.com/user-attachments/assets/c00e3b0c-e056-4121-bc1a-d76f24a9c963" />


Прилагаю скриншот что после создания секретного файла изер под именем студент2 имеет права 

 ls -l у меня не показал + но должен был, т. к ASL подразумевая расширенненые списки контроля доступа, важно это потому что 
 дает подсказку что права выдавались в ASL 

 До ASL
 
 <img width="606" height="75" alt="image" src="https://github.com/user-attachments/assets/b15a437a-e63e-4def-aa9d-e8a539056fea" />
После 

<img width="498" height="60" alt="image" src="https://github.com/user-attachments/assets/3ee3b291-4963-4d9e-acde-8641867bffdb" />

 Удаление 

 <img width="565" height="67" alt="image" src="https://github.com/user-attachments/assets/c9bf961c-0b3b-4a85-b207-81638d2582ce" />

 Я считаю что это поможет нам избежать утечки КДИ, т.е выдавать сразу нужные права а не назначать абсолютно все, удобнее потому что можно выдавать права конкретному пользователю  
