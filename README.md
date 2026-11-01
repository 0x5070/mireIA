#  MireIA v0.2-alpha

MireIA es un asistente de voz local, privado y modular diseñado para Linux. Combina la potencia de **Ollama** (LLM), **Whisper** (STT) y **Piper** (TTS) en una herramienta única con interfaz gráfica.

## Características
- **Privacidad Total:** Todo se ejecuta localmente en tu máquina.
- **Cerebro:** Optimizado para usar `NeuralDaredevil-8B` u otros modelos de Ollama.
- **Voz Fluida:** Integración con Piper para una respuesta de voz casi instantánea.
- **Instalador Universal:** Gestión automática de entornos virtuales y dependencias.
- **Panel de Control:** Interfaz gráfica para configurar personalidad y modelos.

## Instalación Rápida
Asegúrate de tener Python3 y `tkinter` instalados:
```bash
sudo apt install python3-tk python3-venv  # En Debian/Ubuntu
python3 instalador_mireia

## Observaciones
Escribo esto a 22 de abril de 2026 (MireIA v0.2-alpha).

Aún queda por trabajar en la entrada de voz, la cual no entiende correctamente el español a menos que se le hable con mucha claridad; asimismo, la voz parece tener dificultades con cualquier palabra que no sea española. Al ser una herramienta modular, podéis importar cualquier voz o software de reconocimiento de voz de vuestra preferencia, lo mismo con la IA que hace de "cerebro" (mi GTX 1650 no da para más, tristemente).

Por lo demás, solo pido que se me acredite, a ser posible, si se modifica o usa este software en algún otro sitio. En caso de que se utilice para fines lucrativos, tendría que hacerse bajo mi permiso EXPLÍCITO.

DISCLAIMER: Este proyecto concreto no lo he generado en su totalidad por mi cuenta sino que he utilizado herramientas de IA para acelerar el proceso y aprender a usar librerías con las que no tenía experiencia trabajando con anterioridad.
