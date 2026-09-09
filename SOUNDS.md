# Звуки: джерела і ліцензії

Усе взято з freesound.org з фільтром ліцензії **CC0 (Public Domain)**.
Атрибуція не потрібна, комерційне використання дозволене. Список нижче
на випадок, якщо колись треба буде довести походження.

| Файл | Freesound ID | Оригінальна назва | Автор |
|---|---|---|---|
| step1.mp3 | 475859 | ESE - Foot Step - Concrete 2 | EpicSoundEffects |
| step2.mp3 | 475861 | ESE - Foot Step - Concrete 5 | EpicSoundEffects |
| step3.mp3 | 475863 | ESE - Foot Step - Concrete 6 | EpicSoundEffects |
| step4.mp3 | 475864 | ESE - Foot Step - Concrete 8 | EpicSoundEffects |
| step_wood1.mp3 | 390684 | PasosMaderaDuro (перший крок) | Tagiri |
| step_wood2.mp3 | 390684 | PasosMaderaDuro (другий крок) | Tagiri |
| ui.mp3 | 677861 | UI Button Click | el_boss |
| pickup.mp3 | 822565 | Picking Up A Small Item | qubodup |
| type.mp3 | 160678 | typewriter | BMacZero |
| quest.mp3 | 242501 | Powerup/success | GabrielAraujo |
| dig1.mp3 | 651292 | Digging in wet course sand (1) | f3bbbo |
| dig2.mp3 | 651293 | Digging in wet course sand (2) | f3bbbo |
| found.mp3 | 659677 | Shiny Object of Value - Rare Loot Find | LilMati |
| shutter.mp3 | 270435 | shutter click canon eos 5D | chrisvink |
| door.mp3 | 778462 | Wooden_Door_Squeak_04 | BlondPanda |
| gulp.mp3 | 445970 | Drink / Drinking liquid | Breviceps |
| strum.mp3 | 315706 | AcousticGuitar-C-Chord | spitefuloctopus |
| crowd.mp3 | 653920 | Small Crowd Walla | IENBA |

Сторінка будь-якого з них: `https://freesound.org/s/<ID>/`

## Обробка

Усе зведено в моно 32 кГц, обрізано по тиші на початку, з коротким фейдом
у кінці щоб не було клацання, і вирівняно по піку (кроки приблизно -4.4 dB,
кліки тихіші, знахідка і квест голосніші). Бітрейт 48-64 кбіт/с.

`crowd.mp3` зроблено як безшовна петля: хвіст перехрещено з початком,
тому стик не чути.

## Що куди пішло

Шістнадцять коротких звуків вшиті в HTML як base64, це +116 КБ до файлу.
`crowd.mp3` (173 КБ) лежить окремо і має бути в репо поруч з `Music.mp3`.

## Про Pixabay

Pixabay закритий Cloudflare для будь-якого запиту не з браузера, тому звідти
нічого не вийшло витягти. Freesound з фільтром CC0 дає ту саму юридичну
чистоту: public domain, без атрибуції, без обмежень на комерцію. Для
брендового проєкту Optimum це так само безпечно.
