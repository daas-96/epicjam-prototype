# Epic MegaJam - Prototype Project

Proyecto de entrenamiento y plantilla base para la **Epic MegaJam** utilizando **Unreal Engine 5**.

---

## 🛠️ Herramientas Gratuitas Recomendadas

* **Motor:** Unreal Engine 5.4+ (Instalado en `D:\Epic Games\`)
* **Control de versiones:** Git + Git LFS
* **3D / Modelado:** Blender
* **Audio / SFX:** jfxr / Bfxr / Freesound
* **Música:** LMMS / Bosca Ceoil / Audacity
* **Assets:** Fab / Quixel Megascans / Kenney.nl (CC0)

---

## 📂 Flujo de Trabajo con Git y Unreal Engine

1. **Guardar cambios en Unreal:**
   * Antes de hacer commit, guarda todos los niveles y Blueprints (`File > Save All`).
2. **Revisar estado:**
   ```bash
   git status
   ```
3. **Crear commit:**
   ```bash
   git add .
   git commit -m "Mecánica implementada: descripción del cambio"
   ```
4. **Git LFS:**
   * Los archivos `.uasset` y `.umap` se gestionan automáticamente a través de Git LFS gracias a `.gitattributes`.

---

## 🎮 Prototipo de Entrenamiento: "El Escape de la Bóveda"

- [ ] Crear proyecto base en UE5 (Third Person Template).
- [ ] Implementar Actor Batería (Blueprint con Overlap y rotación).
- [ ] Crear HUD (UMG) con contador de baterías y temporizador.
- [ ] Configurar zona de peligro (Láser / Trampa).
- [ ] Crear puerta interactiva con tecla 'E'.
- [ ] Probar empaquetado para Windows (Package Project).
