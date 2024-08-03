<p align="center">
  <strong>DESAFIO 6 BOOTCAMP DEVOPS</strong>
</p>

---

A continuación está el proyecto del desafío a realizar:

[6 - Ansible proyecto modular.pdf](https://github.com/user-attachments/files/16478190/6.-.Ansible.proyecto.modular.pdf)

---

**_Se lanza el playbook con la siguiente línea de comando:_**


ansible-playbook -i inventory.ini playbooks/site.yml



**_Jenkins_**


Para utilizar un archivo Jenkins, sigue estos pasos:

Crear un Pipeline: Primero, deberás crear un nuevo pipeline en Jenkins. Durante la configuración del pipeline, especifica el archivo Jenkins que quieres utilizar.

Configurar SSH: Asegúrate de que el controlador de Ansible tenga configuradas las credenciales SSH necesarias para acceder al host donde se ejecutará el pipeline. Esto incluye la configuración de las claves públicas y privadas para permitir la comunicación segura entre Jenkins y el servidor.

Ejecutar el Pipeline: Una vez configurado el pipeline y las credenciales SSH, puedes ejecutar el pipeline desde Jenkins. Esto permitirá que el pipeline realice las tareas definidas en el archivo Jenkins en el entorno especificado.



**Diagrama de flujo de lo realizado en el desafío:**

<u>[![desafio-6-foto.png](https://i.postimg.cc/nLwvX6Zg/desafio-6-foto.png)](https://postimg.cc/XZdZh1rk)</u>