<h3>4.8. Database Design</h3>

<b>Entities:</b>
Con respecto a la elaboración del diseño de la base de datos, hemos tenido que analizar el inmerso panorama general el cual nuestro proyecto
se va a estar adentrando para canalizar y cerciorar que datos se estarán utilizando para equiparar el orden y la consistencia del mismo logrando ofrecer un flujo óptimo al momento de alojarlos. Es por ello que, en base a ello, podremos identificar cuales vendrían a ser nuestras entidades de las cuales serán participes para nuestro proceso de modelamiento respectivamente; estos vendrían a ser los siguientes:

<p><b>- Entity users:</b> Son los datos pertenecientes a los usuarios que ingresarán a solicitar sus consultas nutricionales.</p>
<p><b>- Entity admins:</b> Es el equipo de desarrollo, creadores de la aplicación de los cuales administran cualquier eventualidad.</p>
<p><b>- Entity forums:</b> Repositorio donde están las opiniones de las personas hacia el enfoque de la atención brindada.</p>
<p><b>- Entity user_support:</b> Facilita el seguimiento de los problemas o consultas de los usuarios, lo que permite un proceso de resolución mas eficiente y efectivo por parte del equipo de soporte.</p>
<p><b>- Entity nutrisionists:</b> Son los datos que pertenecen al staff de nutricionistas que asesoran a los usuarios.</p>
<p><b>- Entity meal_plan:</b> Determina de manera descriptiva la composición de los platillos para un tipo de plan alimenticio.</p>
<p><b>- Entity meal_register:</b> Son los datos que se registran del plan alimenticio y platillos que el mismo usuario puede elegir.</p>
<p><b>- Entity foods:</b> Es el registro de los datos consistentes acerca del valor nutricional de los platillos .</p>
<p><b>- Entity exercise_plan:</b> Aloja los diversos ejercicios físicos que se pueden encontrar en los planes deportivos.</p>
<p><b>- Entity exercise_register:</b> Proporciona el registro de las elecciones que tome el usuario en relación al plan y los ejercicios que desea realizar.</p>
<p><b>- Entity exercises:</b> Establece y determina que la información de los ejercicios así como el tipo al que pertenece.</p>

<br>
<b>Atributes:</b>

<b>- Entity users:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_user | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| first_name | <center>NVARCHAR(25)</center> | <center>YES</center> | <center>NO</center> |
| last_name | <center>NVARCHAR(30)</center> | <center>YES</center> | <center>NO</center> |
| email | <center>NVARCHAR(70)</center> | <center>YES</center> | <center>NO</center> |
| password| <center>NVARCHAR(20)</center> | <center>YES</center> | <center>NO</center> |
| date_registration | <center>NVARCHAR(9)</center> | <center>YES</center> | <center>NO</center> |
| forums_id_forum | <center>INTENRGER</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |
| admins_id_admin | <center>INTENGER</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |
| nutritionists_id_nutritionist| <center>INTENGER</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |

<br>

<b>- Entity admins;</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_admin| <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| admin_name | <center>NVARCHAR(60)</center> | <center>YES</center> | <center>NO</center> |
| admin_last_name | <center>NVARCHAR(30)</center> | <center>YES</center> | <center>NO</center> |
| email | <center>NVARCHAR(70)</center> | <center>YES</center> | <center>NO</center> |
| phone_number | <center>NVARCHAR(9)</center> | <center>YES</center> | <center>NO</center> |

<br>

<b>- Entity forums:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_forum | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| title | <center>NVARCHAR(40)</center> | <center>YES</center> | <center>NO</center> |
| description | <center>NVARCHAR(100)</center> | <center>YES</center> | <center>NO</center> |
| publication_date | <center>DATE</center> | <center>YES</center> | <center>NO</center> |

<br>

<b>- Entity user_support:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| admins_id_admin | <center>INTENGER</center> | <center>YES</center> | <center>YES (and it`s a FK too)</center> |
| forums_id_forum | <center>INTENGER</center> | <center>YES</center> | <center>YES (and it`s a FK too)</center> |

<br>

<b>- Entity nutritionists:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_nutritionist | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| first_name | <center>NVARCHAR(25)</center> | <center>YES</center> | <center>NO</center> |
| last_name | <center>NVARCHAR(30)</center>| <center>YES</center> | <center>NO</center> |
| email | <center>NVARCHAR(70)</center> | <center>YES</center> | <center>NO</center> |
| phone | <center>NVARCHAR(9)</center> | <center>YES</center> | <center>NO</center> |
| description | <center>NVARCHAR(100)</center> | <center>NO</center> | <center>NO</center> |
| starting_time | <center>DATETIME</center> | <center>NO</center> | <center>NO</center>|
| final_schedule | <center>DATETIME</center> | <center>NO</center> | <center>NO</center>|

<br>

<b>- Entity meal_plan:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_meal | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| plan_name | <center>NVARCHAR(50)</center> | <center>YES</center> | <center>NO</center> |
| description |<center>NVARCHAR(100)</center>| <center>YES</center> | <center>NO</center> |
| date_created | <center>DATE</center>| <center>YES</center> | <center>NO</center> |
| target_daily_calories | <center>REAL</center> | <center>YES</center> | <center>NO</center> |
users_id_user | <center>INTENGER</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |

<br>

<b>- Entity meal_register:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| food_id_food | <center>INTENGER</center> | <center>YES</center> | <center>YES (and it`s a FK)</center> |
| meal_plan_id_plan | <center>INTENGER</center> | <center>YES</center> | <center>YES (and it`s a FK)</center> |

<br>

<b>- Entity foods:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_food | <center>INTENGER</center> | <center>YES</center> | <center>YES</center>|
| food_name| <center>NVARCHAR(35)</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |
| description| <center>NVARCHAR(100)</center> | <center>YES</center> | <center>NO</center> |
| nutritional_value | <center>INTENGER</center> | <center>YES</center> | <center>NO</center> |

<br>

<b>- Entity exercise_plan:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_exerplan | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| exercise_plan_name | <center>NVARCHAR(35)</center> | <center>YES</center> | <center>NO</center> |
| description | <center>NVARCHAR(100)</center> | <center>YES</center> | <center>NO</center> |
| date_of_creation | <center>DATE</center> | <center>YES</center> | <center>NO</center> |
| duration_exercises | <center>DATETIME</center> | <center>YES</center> | <center>NO</center> |
| users_id_user | <center>INTENGER</center> | <center>YES</center> | <center>NO (It`s a FK)</center> |

<br>

<b>- Entity exercise_register:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| exercises_id_exercises | <center>INTENGER</center> | <center>YES</center> | <center>YES (and it`s a FK)</center> |
| exercise_plan_id_exerplan | <center>BIGINT</center> | <center>YES</center> | <center>YES (and it`s a FK)</center> |

<br>

<b>- Entity exercises:</b>
| <center>Attribute</center> | <center>Type</center> | <center>Is mandatory?</center> | <center>Is Primary Key</center>|
|--- |--- |--- |--- |
| id_exercises | <center>INTENGER</center> | <center>YES</center> | <center>YES</center> |
| exercise_name | NVARCHAR(20) | <center>YES</center> | <center>NO</center> |
| description | <center>NVARCHAR(100)</center> | <center>YES</center> | <center>NO</center> |
| type_exercise | <center>NVARCHAR(40)</center> | <center>YES</center> | <center>NO</center> |

<br>

<h3>4.8.1. Database Diagram</h3>

<div  align='center'>
<img  src="https://i.ibb.co/88KsX2v/DB-Nourishify-UPC-App-Web-2023-09-16-09-09.png"  alt="Database_Diagram"  width="900"  height="700">

<center><p>Link del diagrama de base de datos: <a  href="https://my.vertabelo.com/doc/rnFl5uF8NckqxD1cMZxb2hImLU6IESSS">https://my.vertabelo.com/doc/SnSuNS8DcPIuEpd1V0yLvb2mXNdmG2Jr</a></p>

<div display="flex" align="right" >
   </br></br>
   &lt;
   <a href="./7-software-object-oriented-design.md">Previous</a>
   &boxh;
   <a href="../chapter-5/1-software-configuration-managment.md">Next</a>
   &gt;
   </br></br>
</div>
