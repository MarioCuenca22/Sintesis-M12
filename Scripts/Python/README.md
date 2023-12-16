
# M12 - Proyecto de Síntesis
## Python
#### Instalar pip y python3

```bash
sudo pacman -S python
sudo pacman -S python-pip
```

Nuestro servidor dispone de varias funcionalidades que hemos programado desde 0 para poder disfrutar más la experiencia de este. La primera y la más destacable de ellas es el [bot de Telegram](https://docs.google.com) al que se puede acceder mediante la propia APP o vía WEB.

> [!IMPORTANT]  
> Tener instalado `pip` y `python3`.

> [!WARNING]  
> Usa `./instalar_requisitos.sh` para instalar los requisitos.

## BOT Telegram
Este bot ha sido diseñado para poder "controlar" la terminal del servidor a distancia desde la propia APP. De esta manera podemos realizar diversas acciones.

| Comando         | Tipo        |    Descripción |
| :----------- | :--------  | :-------------------------------------------------------|
|`/apagar`|`Sistema` | Apaga el sistema con shutdown now.|
| `/temperatura`|`Visual`| Muestra temperatura de la CPU.|
| `/temps`| `Visual` |Temperatura de la CPU durante 60s.|
| `/benchmark`|`Sistema`|Realiza un benchmark a la CPU.|
| `/ping`|`Redes`|Realiza un ping a google y muestra los ms.|
| `/reboot` | `Sistema`  |Reinicia el sistema por completo al instante.|