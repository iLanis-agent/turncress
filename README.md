# Turncress 1.0 TEST
Native Android Dotchi-Loop. These small boards are original generated layouts. Android 8+ (min 26), target 35. Package com.gg007.turncress.

## Rules
Dotchi-Loop. Draw one closed, noncrossing, unbranched orthogonal loop through cell centers. Visit every white circle and avoid every black circle. In each outlined room, all white circles must be straight or all must be right-angle turns. Different rooms choose independently. The rule applies only to white circles, not to ordinary cells. Room borders may be crossed, and a room may be re-entered. Ordinary cells are optional; black circles may lie inside or outside the enclosed loop. Twelve original unique 4x4 room/circle boards and twelve distinct loops. Tap gaps between centers to toggle roads. Undo/reset/next/levels and saved loop palette/room letters.

## Download and status
https://mega.co.nz/#!dc11GBIJ!ktdw4xjcLCN5s-JwZkMpTdmSJJeR1HlzoJxS0vZc1ic
APK SHA256 a8e8ce1cc07f6e9226936637d6d8f4067179aa45157288fcca6d7ecbc91069f0; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Original portable generator enumerates all 213 simple cycles on a 4x4 cell-center grid and creates twelve uniquely constrained original room/circle layouts. Independent Java ordered-cycle tracing agrees with production degree/BFS topology on ALL 16,777,216 edge masks. Independent ordered-path signed-step turning checks agree with production neighbor alignment on all 213 loops across twelve boards; each has exactly one solution. Another 120,000 random/invalid room/white/black-mask cases, 288 single-edge mutations, bounds, solved lock and solve/undo/replay/reset pass. Archived generator reproduces levels.json and all-cycles.json byte-for-byte; archived Java passes. Drawing adapter tests actual road taps, undo/replay/next/levels/menu/settings/privacy and saved palette/room letters/completion. Six drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry and semantic review of all 166 prior studio cards found no Dotchi-Loop match. Sunbriar chooses sun versus moon visits and alternates between rooms; Bendhollow counts bends per room; Signalfern gives fixed color turn/straight and arm sums. Turncress instead infers one shared turn-or-straight choice for every white circle in each room, with mandatory white visits and forbidden black cells. Known Nikoli Dotchi-Loop genre, not a global invention. Primary rules https://www.nikoli.co.jp/en/puzzles/dotchi_loop/ define the selected behavior. No source puzzle copied; original generated room/circle layouts. Recovered repository corpus remains partial.

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated room/white-circle/black-circle clues and road solutions. javac -d /tmp/turn-test src/com/gg007/turncress/Board.java BoardTest.java and java -cp /tmp/turn-test com.gg007.turncress.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Turncress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Loop palette, room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/cr1k54a11qnd-turncress-source-archive, including exact cumulative 166-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/turncress holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
