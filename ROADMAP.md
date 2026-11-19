# Roadmap

Buckwheat Sort is the first game of a small portal of low-stimulation, mindful repetitive activities:
something calm to do with your hands instead of scrolling social media. No artificial productivity, just rest.
Hours are rough estimates (about 65 h in total).

## 1. Code structure and tests (~6 h)
- [ ] Move the game logic out of `buckwheat.html` into its own JavaScript modules (grains, scoring, levels).
- [ ] Unit tests for scoring, level progression and the timer.
- [ ] Lint and format checks, run on every push (GitHub Actions).

## 2. Game portal (~8 h)
- [ ] Start page with a list of games; Buckwheat Sort is the first one.
- [ ] Shared code for all games: profile, language (UA/EN, then PL), sound, saving progress.
- [ ] One common look and feel, works on phone and desktop, installable as an app (PWA, offline).

## 3. More mindful games (~18 h)
Simple, repetitive, no pressure. Each one has its own gesture and its own soft sounds.
- [ ] Shelling peas and beans (tap and drag): open the pods, drop the peas into a bowl.
- [ ] Cracking nuts: crack the shell, take out the kernel, remove the inner skins.
- [ ] Sorting seeds and dried fruit: lentils, chickpeas and other seeds, dried berries, nuts - each kind into its own bowl.
- [ ] Sorting buttons (drag and drop): by colour, size and shape, with a layout that still works on a small phone screen.
- [ ] Laundry pile (swipe and drag): sort a big pile of clothes, then fold it.
- [ ] Knitting: choose a yarn and an object (sweater with holes, dense sweater, skirt, dress, socks, hat), then
      knit with a slow circular hand movement and watch it grow.
- [ ] Idea to try later: washing pebbles.

## 4. Mindful mode (~4 h)
- [ ] A setting for a fully mindful version: no timers, no losing, no daily tasks, no streaks.
- [ ] Leave at any moment, progress is kept.
- [ ] Gentle interaction sounds: grains touching a bowl, water running, fabric rustling.
- [ ] Calm colours and slow animations.

## 5. Accounts (~10 h)
- [ ] Guest mode stays: play without an account.
- [ ] Optional account with only a nickname and a password. No email, no real name.
- [ ] Random nickname generator (for example "Healthy Futuristic Cucumber").
- [ ] Passwords stored only as a secure hash; a one-time recovery code instead of email recovery.
- [ ] Small backend and database for accounts and progress, with rate limits on login.
- [ ] Progress saved to the account, so it is not tied to one browser; guest progress can be moved into a new account.

## 6. Friends (~8 h)
- [ ] Add friends by nickname, accept or decline requests.
- [ ] See friends' progress and best scores per game.
- [ ] Weekly friends leaderboard.

## 7. Buckwheat Sort gameplay (~6 h)
- [ ] Difficulty modes, with new kinds of bad grains and debris in the harder ones.
- [ ] Wind: from time to time it mixes the grains on the table.
- [ ] Streak: a bonus for a series of correct sorts in a row (only outside mindful mode).

## 8. Progress and stats (~4 h)
- [ ] Stats screen per game: games played, accuracy, time spent, best level over time.
- [ ] Export and import progress.

## 9. Accessibility (~4 h)
- [ ] Bigger touch targets and a high-contrast mode.
- [ ] Sound and vibration on/off switches.
- [ ] Keyboard controls on desktop.
