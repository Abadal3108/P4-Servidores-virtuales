1. Crea dos sitios web que compartirán IP y puerto, pero tendrán nombres DNS distintos
para acceder a ellos. El nombre del primer dominio será daw.gimbernat.eug.es y el
segundo tunombreyapellidos.gimbernat.eug.es, donde “tunombreyapellidos” contiene
la inicial de tu nombre, el primer apellido, y la inicial de tu segundo apellido. De esta
manera, si tu nombre es: Francisco Mesas Cervilla, el domino quedaría:
fmesasc.gimbernat.eug.es.
• En el primer caso, daw.gimbernat.eug.es tendrá su directorio base en
/var/www/daw/ conteniendo una página llamada index.html que ponga el
nombre de la clase como título con un archivo css para aplicarle estilos al título.
• En el segundo caso, fmesasc.gimbernat.eug.es tendrá su directorio base en
/var/www/fmesasc/ (el equivalente para vuestros nombres), conteniendo una
página llamada index.html que contenga vuestro currículum aplicándole un
estilo css para que se visualice correctamente.
Para ello, tendrás que crear un archivo de configuración (copiado de 000-default.conf)
para cada uno de los dominios. Recuerda que con a2ensite puedes crear los enlaces
simbólicos necesarios para añadir esta configuración a la ejecución de apache.


![image](https://user-images.githubusercontent.com/113515441/202519526-1184556f-fb82-43ac-8793-1ee457470176.png)
![image](https://user-images.githubusercontent.com/113515441/202519535-0cf4f060-81f8-4ddf-ba7f-4acf94b3b5d2.png)
![image](https://user-images.githubusercontent.com/113515441/202519557-e362a1b8-8bd3-4658-9fd5-99abdcecc359.png)
![image](https://user-images.githubusercontent.com/113515441/202519576-b570c4cb-126a-44c8-8913-9893f3fc3f72.png)
![image](https://user-images.githubusercontent.com/113515441/202519599-480fe8e9-ef5d-4f6e-8f67-df638b8833fe.png)
![image](https://user-images.githubusercontent.com/113515441/202519608-c67a4f3f-4933-4901-8125-2bfd0447add0.png)
![image](https://user-images.githubusercontent.com/113515441/202519651-9210f300-a238-476b-b301-8b1429933cd7.png)
![image](https://user-images.githubusercontent.com/113515441/202519664-2bace786-1e9c-4975-a0e5-94f83ec91497.png)![image](https://user-images.githubusercontent.com/113515441/202519676-18cdf29b-b7a9-4cb0-aa7c-e1af00bc18f4.png)
![image](https://user-images.githubusercontent.com/113515441/202519718-b5886a2d-611f-4cc5-8506-dc64dd2a0f60.png)
![image](https://user-images.githubusercontent.com/113515441/202519753-c9e34946-994d-488b-8841-4090377b44db.png)
![image](https://user-images.githubusercontent.com/113515441/202519765-e304e360-e7c7-403e-b0fe-1d89206d0d5c.png)
![image](https://user-images.githubusercontent.com/113515441/202519811-c2a7625b-e3d2-448f-b599-abf59715a9ba.png)
![image](https://user-images.githubusercontent.com/113515441/202519840-edb11f30-1193-4d0d-ad8b-42165e317829.png)
![image](https://user-images.githubusercontent.com/113515441/202519870-bf220429-3c6b-4cd4-bcf9-027c18e90339.png)
![image](https://user-images.githubusercontent.com/113515441/202519896-3951bf64-2792-45b7-9d2d-9fd2b299fe27.png)
![image](https://user-images.githubusercontent.com/113515441/202519910-27d7402a-1ffa-45fc-9d72-e86a51fc4e35.png)
![image](https://user-images.githubusercontent.com/113515441/202519935-48b3736b-3547-44d9-83b5-5846a9a9b31f.png
![image](https://user-images.githubusercontent.com/113515441/202519973-b96ac7a6-7124-4364-82e8-1ff5887fb917.png)


