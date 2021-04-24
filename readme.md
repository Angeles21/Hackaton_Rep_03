1. ¿Para que sirve la validación de formularios?

- La validación es el proceso mediante el cual el desarrollador anticipa   
  potenciales errores o fallas por parte del usuario (lo cual de ser enviado sin ninguna revisión, hace que el trabajo de quien maneje la data aún más engorroso). Estableciendo una serie de protocolos o pautas que limiten/ informen al usuario de los errores que está cometiendo, puede asegurarse que la calidad de la información no se verá comprometida. 
  
  Ex: Es oblgatorio que los bancos soliciten DNI a los usuarios para revisar su historal crediticio.

  ---

2. ¿Cuáles son los problemas al no validar un formulario?

- La información proporcionada por el usuario (ya sea intencionalmente o 
  no) puede ser errónea o falsa, y esta data puede alimentar el banco de datos que manejemos en el futuro.

- No es considerado como buenas prácticas el tener formularios que no
  tengan estándares y protocolos de seguridad pre establecidos para validar información, ya que el usuario podría ignorar la importancia de ciertos campos. 

---

3. ¿Cuáles son los beneficios?

- No depende exclusivamente de JavaScrip si se utilizan los controles 
  básicos con lenguaje HTML5 (aunque es recomendable utilizarlo para facilitar el envío de datos). 

- Permite campos personalizados, los cuales deberían también de tener en
  cuenta la calidad de la experiencia de usuario.

- De realizarse de la manera correcta, la calidad de información obtenida 
  será precisa y organizada, lo cual facilitará el trabajo de quienes ven ese lado del servidor. 
  
  Ex: En el campo de "Código postal" solo pueden introducirse 5 números. 

- Protege a los usuarios de amenazas potenciales solicitando elementos
  como contraseñas seguras que combinen cierto tipos de caractéres o la convalidación de su registro por medio de un mensaje de texto o correo electrónico. 

  Ex: "Tu contraseña debe tener como mínimo 10 caracteres, dentro de ellos
  uno debe de ser especial y otro debe contener una mayúscula o número."