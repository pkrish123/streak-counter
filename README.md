# streak-counter

## About
This is a streak counter library, to be used when implementing functionality such as calculating how many days in a row you've accessed a particular site.

<img src="https://github.com/pkrish123/streak_counter_example.png" alt="screenshot of streak demo" width="200" />

## Install
```npm
npm install streak-counter
```

## How to Use streak-counter
```typescript
import {get_streak, get_streak_duration, increment_streak} from 'streak_counter'

cont streak = get_streak()

cont streak_duration = get_streak_duration()

cont streak = increment_streak()

```