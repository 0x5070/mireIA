# MireIA v0.2-alpha

Asistente de voz local, privado y modular para Linux.
Local, private, modular voice assistant for Linux.

---

## 🇪🇸 Español

### Descripción
MireIA combina Ollama (LLM), Whisper (STT) y Piper (TTS) en una herramienta única con interfaz gráfica, pensada para ejecutarse íntegramente en local.

### Características
- **Privacidad total:** todo se ejecuta localmente en tu máquina.
- **Cerebro:** optimizado para usar `NeuralDaredevil-8B` u otros modelos de Ollama.
- **Voz fluida:** integración con Piper para una respuesta de voz casi instantánea.
- **Instalador universal:** gestión automática de entornos virtuales y dependencias.
- **Panel de control:** interfaz gráfica para configurar personalidad y modelos.

### Instalación
Asegúrate de tener Python 3 y `tkinter` instalados:
```bash
sudo apt install python3-tk python3-venv  # En Debian/Ubuntu
python3 mireIA.py
```

### Estado actual
Aún queda por trabajar en la entrada de voz, que no entiende correctamente el español salvo que se le hable con mucha claridad; la voz también tiene dificultades con palabras que no sean españolas. Al ser modular, puedes importar cualquier voz o software de reconocimiento de tu preferencia, lo mismo con el modelo que hace de "cerebro" (mi GTX 1650 no da para más).

---

## 🇺🇸 English

### Overview
MireIA combines Ollama (LLM), Whisper (STT), and Piper (TTS) into a single tool with a graphical interface, designed to run entirely offline.

### Features
- **Full privacy:** everything runs locally on your machine.
- **Brain:** optimized for `NeuralDaredevil-8B` or other Ollama models.
- **Fluid voice:** Piper integration for near-instant voice responses.
- **Universal installer:** automatic management of virtual environments and dependencies.
- **Control panel:** graphical interface to configure personality and models.

### Installation
Make sure you have Python 3 and `tkinter` installed:
```bash
sudo apt install python3-tk python3-venv  # On Debian/Ubuntu
python3 mireIA.py
```

### Current status
Voice input still needs work — it doesn't reliably understand Spanish unless spoken very clearly, and the voice also struggles with non-Spanish words. Being modular, you can swap in any voice or speech-recognition software you prefer, the same goes for the "brain" model (my GTX 1650 can't handle much more).

---

## Licencia / License
CC BY-NC 4.0 — atribución requerida, uso comercial solo con permiso explícito del autor. Ver [LICENSE](LICENSE).
CC BY-NC 4.0 — attribution required, commercial use only with the author's explicit permission. See [LICENSE](LICENSE).

**Nota / Note:** este proyecto se ha desarrollado con ayuda de herramientas de IA para acelerar el proceso y aprender librerías nuevas.
This project was built with the help of AI tools to speed up development and learn new libraries.
