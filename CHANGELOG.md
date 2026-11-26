# Changelog · 更新記錄

What changed in 華夏歷史輿圖 (the Historical Atlas of China), newest first. The
reasons behind each change are in `docs/DECISIONS.md` under the numbers given.

## How versions are numbered

`MAJOR.MINOR.PATCH`, for example `0.20.0`.

- **MINOR** goes up when there is something new to see or do: a view, a tool,
  a new body of records (a set of battles, a group of families).
- **PATCH** goes up for fixes, corrections to records, and small additions to
  what is already there.
- **MAJOR** is `0` until the atlas is launched under its own name and
  address. That launch is `1.0.0`. After it, MAJOR goes up only when
  something people already hold would stop working (a shared link, an
  entry's address) or when the range the atlas covers changes.

Every published change gets a version: the number in `package.json`, an entry
here, and a tag `vX.Y.Z` on the commit. The version is shown beside the
atlas's name on the page. Versions before `0.20.0` were assigned afterwards,
from the history of the work: one for each stretch that gave readers
something new, tagged on the last commit of that stretch.

Records can also be corrected through 參與編輯; those changes are listed
entry by entry in the atlas's own history (變更記錄), not here.

## 0.22.0 · 2026-11-25
Banners, and the colour of the age. (#101)

### Added
- A banner for each side of a battle: in the caption, in the chronicle, and
  planted on the map where it was fought; the victor's flies, the loser's is
  lowered. The colour is the one the histories record for that power where
  they record one (秦 black, 劉邦 red, 隋 red, 宋 red, 金 white, the 黃巾 yellow…),
  otherwise its colour on the map; the hint says which, with the sentence.
- The colour of the age: a seal beside the atlas's name and a line under the
  top bar, from what the dynasty recorded of itself. Click the seal for the
  sentence.
- 史源 lists the sixteen records under 服色.

## 0.21.0 · 2026-11-25
Families beyond the ruling line. (#100)

### Added
- Founders' forebears, as far up as their histories go: 司馬懿, 高歡, 宇文泰,
  趙匡胤, 拓跋珪, 李克用, 劉淵, 朱溫, 秦始皇; 蕭道成 to 蕭何, 陳霸先 to 陳寔 and
  曹操 to 曹參 as the histories claim them.
- Kin beside the line: 劉邦's nephew 劉濞, his grandsons, 戚夫人 and 薄姬;
  曹操's sons, daughters and cousins.
- 漢初功臣 (蕭何, 韓信, 張良 and eleven more), 項羽's house, the 夏侯 of 譙, 長孫氏.
- Marriages that join trees: 曹操 and 夏侯惇, 劉備 and 孫權, 李世民 and 宇文邕
  can now be found in 與他人的關係.

### Fixed
- A cousin or kinsman (從弟, 族子) is drawn in their generation with the
  record's own word, instead of as someone's son.

## 0.20.0 · 2026-11-25

### Changed
- The time bar: the buttons that step through the years are large and stand
  at the two ends of the bar; the row of dynasties is one ruler of the whole
  range with short names, the era on screen marked, instead of a row of
  chips that had to be paged. (#99)

### Added
- This changelog, a version number, and the version shown beside the atlas's
  name. (#99)

## 0.19.0 · 2026-11-25
Families of the Sixteen Kingdoms and the Ten Kingdoms. (#98)

### Added
- Thirteen houses of the Sixteen Kingdoms; 後晉, 後漢 with 北漢, and nine of
  the Ten Kingdoms, as rulers and the line between them.
- 太原王氏 and 清河崔氏, with their Northern Wei branches.
- Fifteen more years of birth confirmed from the emperors' own annals.

## 0.18.0 · 2026-11-25
詩人行跡. (#97)

### Added
- A view for 李白, 杜甫 and 蘇軾: 44 poems, each where it was written, with
  the poet's road drawn as the years pass and the basis of each date stated.
- A poet's entry lists their poems.

## 0.17.0 · 2026-11-25
Relationships, and births and deaths on the whole screen. (#96)

### Added
- 與他人的關係: how any two people entered are joined, by descent and marriage.
- The family trees full screen, each person with their years as the timeline
  moves, "?" where a year is not recorded.
- 隴西李氏 above 李淵 (李虎, 西涼's 李暠, 李廣) and the 西魏八柱國.

## 0.16.0 · 2026-11-25
A faster first visit, and links that show what they lead to. (#94, #95)

### Added
- A shared link carries a title, a line and a picture of the map.

### Changed
- The first screen appears at once and the map in about half the time: the
  script comes in pieces, and the first data is asked for together.

## 0.15.0 · 2026-11-25
家族 redrawn as trees. (#93)

### Changed
- 家族 shows every family with someone living at the moment, as drawn trees;
  details only when a person is opened.

### Added
- Houses the histories join are one tree (劉邦 to 光武, 劉備 and 劉裕; 蘭陵蕭氏;
  弘農楊氏 to 隋), with a broken line where the generations are not recorded.
- 世家, a view that follows one great family's story; 琅邪王氏 and 弘農楊氏.

## 0.14.0 · 2026-11-25
家族. (#90, #91, #92)

### Added
- Families at the side of the map: who was whose child, how the throne
  passed, how each person ended and at whose hands, each with its sentence.
  Thirty-nine families.

### Fixed
- Lines between areas no longer run out across the sea.
- The map's credit button is gone; the credit is on the opening screen.

## 0.13.0 · 2026-11-25
Phones, and the people of each event. (#89)

### Added
- A layout for phones and folding phones.
- Each event lists the people in it; any of them can be opened or followed.

## 0.12.0 · 2026-11-25
此時大事, and how the population moved. (#88)

### Added
- What is under way at the moment, above the time bar.
- Population change between censuses, the centre of population, and 38
  recorded migrations drawn as arrows.

## 0.11.0 · 2026-11-25
简体, and a view for territory alone. (#85, #86, #87)

### Added
- A simplified-character version (traditional stays the default).
- 疆域變遷: every change of territory, without the battles.

### Changed
- Playback no longer waits where nothing is recorded.

## 0.10.0 · 2026-11-25
Prefectures, and a page to audit the sources. (#81, #82, #83, #84)

### Added
- Tang to Song by prefecture; the Five Dynasties and Ten Kingdoms and the
  Song–Jin wars drawn at that scale.
- 史源: everything the atlas quotes, listed for checking against the books.

## 0.9.0 · 2026-11-25
Views, and deeper records. (#75, #76, #77, #78, #79, #80)

### Added
- 視角: follow wars, disasters, population, the land, Buddhism or trade.
- 187 disasters, household totals, Buddhist sites, trade routes; reign lists
  for 44 more courts; the source's own words for 121 border changes.

### Changed
- A calmer Watch bar and a more natural reading voice.

## 0.8.0 · 2026-11-25
Sharing, and ways to read the map. (#69, #70, #71, #72, #73, #74)

### Added
- A link to a moment; a strip showing how much is recorded in each era.
- 精華, a run of about a hundred turning points.
- The chart of rise and fall; one place through time; following a person's
  life; captions read aloud; two years side by side; who reigns now.
- Layers for trade routes, Buddhism and disasters.

## 0.7.0 · 2026-11-24
觀史: the atlas plays. (#62, #63, #64, #65, #66, #67, #68)

### Added
- Watch mode, with a camera, captions and playback paced by events; battles
  play out along their routes.
- A hint on everything that can be clicked; answers open at the right.

### Changed
- 3D and playback made faster, from measurements.

## 0.6.0 · 2026-11-24
Population, relief and 3D. (#58, #59, #60, #61)

### Added
- Census households as dots, from the Han treatises to Tang and Song.
- Shaded relief and a 3D view.

## 0.5.0 · 2026-11-24
秦 to 隋 fought through. (#41 to #57)

### Added
- Several hundred battles with routes and sources, from the fall of 秦 to the
  end of 隋, month by month in the busiest stretches.
- Playback speed.

## 0.4.0 · 2026-11-22
Battles behind the border changes. (#37, #38, #39, #40)

### Added
- The battle behind each change of border, with arrows along the routes the
  sources give.

## 0.3.0 · 2026-11-21
The map changes as it is watched. (#21 to #36)

### Added
- Strategic passes; provinces and circuits that change over time; rivers,
  canals, walls and lakes with their dates.
- Border and province changes played out; nominal and actual control as two
  layers; arrows for who advanced where.

## 0.2.0 · 2026-11-21
The whole range. (#15 to #20)

### Added
- 770 BCE to 1279 in overview, with a time bar in eras, a chronicle and a
  page for each dynasty.

## 0.1.0 · 2026-11-15
The Three Kingdoms slice. (#1 to #14)

### Added
- 180 to 280 on a map of commandery seats: territories, people, events and
  sources, a timeline in months, and tools for anyone to correct a record.
