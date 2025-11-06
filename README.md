\ #include "contacto.h"
#include <iostream>

Contacto::Contacto(std::string n, std::string t, std::string c)
    : nombre(n), telefono(t), correo(c) {}

void Contacto::mostrar() const {
    std::cout << "Nombre: " << nombre << "\nTeléfono: " << telefono << "\nCorreo: " << correo << "\n";
}
