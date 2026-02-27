# Live Poll

A real-time, audience polling app. The host creates a poll on their laptop, participants scan a QR code on their phones to vote, and the results appear as a bar chart when the poll is ended.

---

## Stack

| Layer    | Technology                          |
|----------|-------------------------------------|
| Backend  | Python · FastAPI · SQLite (via SQLAlchemy) |
| Frontend | TypeScript · React · Vite (see [this Repo](https://github.com/mochiyaki/livepoll)) |

---

## Getting Started

clone this repo
```
git clone https://github.com/calcuis/livepoll
```

then
```
cd livepoll
```

## Terminal 1
```
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

## Terminal 2
```
npx localtunnel --port 8000
```

*check the localtunnel server status first: https://status.loca.lt
