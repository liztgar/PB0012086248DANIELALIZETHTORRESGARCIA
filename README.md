#include <iostream>
using namespace std;

int main()
{
    int menu = 1;
    int jmn;
    int numc= 0;
    char nombrepaciente;
    int hora;
    int minutos;
    char nombretratamiento;
    char descripcion;
    int preciounitariotrat;
    int cantidad;
    int preciounitario;
    int total;
    int a;

    while (menu == 1)
  {
        cout << "BIENVENIDO AL MENU DE OPCIONES, POR FAVOR ELIJA UNA DE LAS SIGUIENTES OPCIONES" << endl;
        cout << "1-Agendar cita" << endl;
        cout << "2-Modificar cita" << endl;
        cout << "3-Eliminar cita" << endl;
        cout << "4-Lista de citas vigentes" << endl;
        cout << "5-Limpiar pantalla" << endl;
        cout << "6-Salir" << endl;
        cin >> jmn;
        switch (jmn)
        {
        case 1:
            cout << "El numero de cita es" << endl << numc + 1 << endl;
            cout << "Nombre del paciente" << endl;
            cin >> nombrepaciente;
            cout << "Hora del tratamiento" << endl;
            cin >> hora;
            cin >> minutos;
            cout << "Nombre del tratamiento" << endl;
            cin >> nombretratamiento;
            cout << "Anada una descripcion" << endl;
            cin >> descripcion;
            cout << "Precio unitario del tratamiento" << endl;
            cin >> preciounitariotrat;
            cout << "Cantidad del tratamiento" << endl;
            cin >> cantidad;
            cout << "Precio unitario" << endl;
            cin >> preciounitario;
            cout << "Total" << endl;
            cout << "¿Desea salir de la agenda de citas?" << endl;
            cout << "Presione a-Salir y b-Permanecer en esta pagina" << endl;
            cin >> a;
            break;

        }
        
        return 0;
    }
    
}
