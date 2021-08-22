# kunci-tts-api
Rest API untuk mendapatkan kunci jawaban TTS (Teka Teki Silang)

## Documentation
### Endpoint
#### GET Answers
Endpoint untuk mendapakan kunci jawaban tts berdasarkan pertanyaan yang dikirim melalui parameter question (contoh: question=tidak jujur)

```
// Request
GET https://kunci-tts-api.vercel.app/api/answers?question=tidak jujur

// Reponse
{
    "title": "Kunci jawaban TTS Tidak Jujur",
    "total": 25,
    "answers": [
        {
            "stars": 5,
            "word": "CURANG",
            "clue": "Tidak jujur"
        },
        {
            "stars": 4,
            "word": "FAIR",
            "clue": "Sportif, jujur"
        },
        {
            "stars": 4,
            "word": "TRUST",
            "clue": "Buah jujur"
        },
        {
            "stars": 4,
            "word": "SIDIK",
            "clue": "Benar, jujur"
        },
        {
            "stars": 4,
            "word": "HONEST",
            "clue": "Jujur (bahasa Inggris)"
        },
        ... // and more
    ]
}
```

### Postman
```
https://documenter.getpostman.com/view/414747/TzzDJuor
```
