# BHFF Tutoring program - baza znanja

### Uputstvo za lokalno pokretanje dokumentacije
1. Klonirati repozitorijum
```bash
git clone https://github.com/neuralmaticv/bhff-tutoring.git
```

2. Pozicionirati se u direktorijum `bhff-tutoring`
```bash
cd python-docs
```

3. Kreirati virtualno okruzenje i aktivirati ga
```bash
python -m venv env-docs

# za Unix zasnovane operativne sisteme
source env-docs/bin/activate

# za Windows
source env-docs/Scripts/activate
```

4. Instalirati potrebne pakete
```bash
pip install -r requirements.txt
```

5. Pokrenuti dokumentaciju
```bash
mkdocs serve
```

Dokumentacija se pokrece na adresi [localhost:8000](localhost:8000)

