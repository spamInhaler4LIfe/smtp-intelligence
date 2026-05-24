# SMTP-INTELLIGENCE
# An Advanced Email Verifier

A high-performance asynchronous email verification framework using:

- SMTP verification
- MX validation
- SPF/DKIM/DMARC analysis
- Disposable email detection
- Catch-all detection
- Breach intelligence
- Redis caching
- Machine-learning scoring
- FastAPI REST API

## Features

✅ Async SMTP verification  
✅ DNS intelligence  
✅ Disposable detection  
✅ Bulk verification  
✅ Docker support  
✅ Redis cache  
✅ REST API  
✅ CLI interface  
✅ ML risk scoring

---

## Installation

```bash
git clone https://github.com/yourname/advanced-email-verifier.git

cd advanced-email-verifier

pip install -r requirements.txt
```

---

## Run API

```bash
uvicorn api.main:app --reload
```

---

## API Example

```bash
GET /verify?email=test@gmail.com
```

---

## CLI Example

```bash
python cli.py verify test@gmail.com
```

---

## Docker

```bash
docker-compose up --build
```

---

## License

MIT
