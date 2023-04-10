# pdf-js
como crear un pdf con js


en el html agregar <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.3.4/jspdf.min.js"></script>
 
y en js se puede crear con 

const doc = new jsPDF();

doc.text("Hello world!", 10, 10);
doc.save("a4.pdf");

se descarga el pdf automaticamente asi que recomiendo meter el codigo anterior en una funcion y ejecutarlo al clickear un boton
