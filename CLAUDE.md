# Workshop: Spanish

## Purpose

Language workshop for learning Spanish — the most important words and expressions for daily conversation.

## Target Audience

- **Level**: Absolute beginner
- **Native languages**: German, English, Farsi, or Arabic speakers
- **Goal**: Basic Spanish vocabulary and phrases

## Structure

- **10 lessons** covering core vocabulary
- **Interface languages**: Deutsch, English, Farsi, Arabic
- **Teaching language**: Spanish (es-ES)
- **Features**: audio pronunciation, assessments

## Labels

`Language`

## Conventions

- `q` = Spanish example (teaching language)
- `a` = translation in interface language
- Thematic lessons (greetings, numbers, food, etc.)

## Development

```bash
# Generate audio (Edge TTS) for each interface language
bash generate-audio.sh deutsch/spanish
bash generate-audio.sh english/spanish
bash generate-audio.sh farsi/spanish
bash generate-audio.sh arabic/spanish
```

## See Also

- [Open Learn Platform](https://github.com/openlearnapp/openlearnapp.github.io)
- [Workshop Guide](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/workshop-guide.md)
- [Lesson Schema](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/lesson-schema.md)
- [Workshop Creator Plugin](https://github.com/openlearnapp/plugin-workshop-creator)
