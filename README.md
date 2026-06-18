# Spending Tracker

Real-time spending logger with gamification. Track impulse levels, flag spending as aligned or avoidance, set weekly priorities, and watch savings goals fill up in real-time.

## Features

- **Real-time logging** — Log spending as it happens (amount, category, impulse level, optional note)
- **Daily profit tracking** — Enter your daily profit target (£60), see your net performance
- **Day rating** — Auto-calculates Perfect/Good/Bad based on profit vs. spend
- **Impulse tracking** — Categorize each spend as Low, Medium, or High impulse
- **Smart flags** — Mark spending as Aligned (good choices) or Avoidance (gap-filling)
- **Weekly priorities** — Set spending obligations/priorities, track completion %
- **Responsibility rating** — Irresponsible (<50%) / Responsible (50-70%) / Excellent (70%+) / Perfect (100%)
- **Gamified quests** — 7 savings goals that progress with aligned spending
- **Today's dashboard** — See impulse breakdown, category split, aligned vs. avoidance totals
- **Local storage** — All data persists on your device, survives app updates
- **Export/import** — Backup your spending data anytime

## How It Works

**Log tab:** Quick real-time entry — daily profit, amount, category, impulse level, optional note.

**Today tab:** Dashboard showing total spent, daily rating (Perfect/Good/Bad), net profit, impulse breakdown, and category split.

**Priorities tab:** Weekly checklist of spending obligations. Track completion %. See if you're being Responsible or Irresponsible with your priorities.

**Quests tab:** 7 savings goals (Cocktail class, Bouldering, Salsa, Music course, Skateboard gear, Travel fund, BJJ). Progress bars fill as you spend aligned money.

**Settings tab:** Export spending data as JSON, or import from a previous backup.

## The System

**Daily Performance:**
- Perfect: £60 profit + £0 or less spend = net ≥ £60
- Good: £60 profit + £0-£20 spend = net £40-£60
- Bad: Profit missed OR spend > £20 = net < £40

**Weekly Responsibility:**
- Irresponsible: < 50% priorities completed (identity trigger)
- Responsible: 50-70% completed
- Excellent: 70-100% completed
- Perfect: 100% completed

The spending tracker separates **intentional spending** (priorities) from **impulsive spending** (gap-filling). Together with daily profit tracking and savings goals, it creates a system where financial discipline becomes visible and rewarding.

## Install as PWA

**iPhone:**
1. Open in Safari
2. Tap Share (bottom center)
3. Tap "Add to Home Screen"
4. Name it "Spending Tracker"
5. Tap Add

**Android:**
1. Open in Chrome
2. Tap menu (three dots, top right)
3. Tap "Install app"
4. Confirm

The app works offline and saves everything locally.

## Live

[18ventures.github.io/spending-tracker](https://18ventures.github.io/spending-tracker/)
