# programacion-3
progrma qeue calcula el sueldo de una persona que trabaja por horas en una empresa
![image](https://user-images.githubusercontent.com/70080439/217654523-c2bab673-cbcb-40a9-b6fc-ebba4b31e6ae.png)




 //declaracion de variables de entrada
            int horasTrabajadas;
            float costoHora;
            //declaracion de varibale de salida
            float sueldo;

            //DATOS DE ENTRADA
            horasTrabajadas = int.Parse(txthorastrabajadas.Text);
            costoHora = float.Parse(txtcostoporhora.Text);

            //DATOS DE PROCESO
            sueldo = horasTrabajadas * costoHora;

            //DATOS DE SALIDA
            txtsueldo.Text = Convert.ToString(sueldo);
        }
