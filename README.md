# Porovnání komprese obrazu: SVD vs. Wavelety

Tento projekt se zabývá implementací a srovnáním dvou metod pro kompresi obrazových dat:
1. **Singulární rozklad (SVD)**
2. **Diskrétní waveletová transformace (DWT)**

Cílem je analyzovat kvalitu rekonstrukce a výpočetní náročnost obou algoritmů na sadě testovacích obrázků s různým rozlišením (od 12 MPx po 50 MPx).

## Požadavky

Využíval jsem **Python 3.10.12** a několik balíčků.

### Instalace knihoven
Pro instalaci všech potřebných balíčků spusťte:

```bash
pip install numpy opencv-python PyWavelets matplotlib scikit-image