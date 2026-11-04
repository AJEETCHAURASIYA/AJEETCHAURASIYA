# GitHub profile README — kaise lagayein

Ye files aapke **GitHub profile repo** (`AJEETCHAURASIYA/AJEETCHAURASIYA`) ke liye hain, is website repo ke liye nahi.

## Files
| File | Kya karti hai |
|---|---|
| `README.md` | Profile page: animated header, typing text, badges, tech stack, interactive 3D model, journey diagram, stats, 3D contribution city, snake |
| `.github/workflows/snake.yml` | Snake animation banata hai (`output` branch) — har 12 ghante |
| `.github/workflows/summary-cards.yml` | Stats cards banata hai (`profile-summary-card-output/`) — har 12 ghante |
| `.github/workflows/profile-3d.yml` | 3D contribution city banata hai (`profile-3d-contrib/`) — roz |

## Steps
1. GitHub par **public** repo banaiye jiska naam bilkul aapke username jaisa ho: `AJEETCHAURASIYA`.
2. Is folder ki saari files usi structure mein upload kijiye:
   - `README.md` → repo ki root mein
   - teeno `.yml` → repo mein `.github/workflows/` folder ke andar
3. Repo → **Settings → Actions → General → Workflow permissions → "Read and write permissions"** → Save.
4. Repo → **Actions** tab → teeno workflows ko ek-ek baar **Run workflow** se chalaiye.

Pehli baar workflows chalne tak snake, stats cards aur 3D city ki images khaali dikhengi — ye normal hai.

## Badalna ho to
- Naam / lines: `README.md` ke upar `capsule-render` aur `readme-typing-svg` wale links mein text badliye (space = `+` ya `%20`).
- Skills: `skillicons.dev/icons?i=...` mein icon names jodiye/hataiye (list: https://skillicons.dev).
- 3D model: ` ```stl ` block GitHub par khud ghoomne wala 3D viewer banta hai.
