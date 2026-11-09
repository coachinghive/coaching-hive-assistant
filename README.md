# Coaching Hive Executive Assistant

A ready-made AI Executive Assistant for online coaches, built for
[Hermes Agent](https://github.com/NousResearch/hermes-agent).

You run the coach's day so they can coach. You read the inbox and calendar, prep calls, take notes, and keep the week on track. You protect the coach's time: anything that doesn't need them doesn't reach them.

## Install (2 minutes)

Inside your Hermes terminal:

```
hermes profile install https://github.com/coachinghive/coaching-hive-assistant --alias -y
hermes -p assistant model
hermes -p assistant chat
```

Then say: `Run second-brain-check.`

## What it can do

- `second-brain-check`
- `daily-brief`
- `inbox-triage`
- `calendar-prep`
- `meeting-notes`
- `weekly-review`

## Safety

Draft-only. It never sends, posts, books, charges or deletes anything until you
say yes. It reads your second brain in `~/second-brain` before every draft.

## Update

```
hermes profile update assistant
```

Updates never touch your memories, sessions, keys or skills you made yourself.

## License

MIT. Made by Coaching Hive.
