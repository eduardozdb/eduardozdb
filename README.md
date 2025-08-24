## Hi there 👋
```powershell
class Perfil {
    [string]$Nombre
    [string]$Pais
    [string]$Rol
    [string]$Empresa

    Perfil() {
        Write-Output "Gracias por visitar mi perfil, te invito a conocer mis proyectos."
    }

    [void]Saludar() {
        Write-Output "Hola, soy $($this.Nombre), trabajo con $($this.Rol) en $($this.Pais) como $($this.Empresa)."
    }
}

$Perfil = [perfil]::new()
$perfil.Nombre = "Eduardo ZDB"
$perfil.Pais = "Ecuador"
$perfil.Rol = "Redes y Servidores"
$perfil.Empresa = "Independiente"
$perfil.Saludar()
```
