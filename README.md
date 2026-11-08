# Anglewren 1.0 TEST
Native Android Angle Loop, triangle/square/pentagon edition. These small boards are original generated layouts. Android 8+ (min 26), target 35. Package com.gg007.anglewren.

## Rules
Angle Loop, triangle/square/pentagon edition. Tap one symbol and then another to toggle the straight link between them. Tap the selected symbol to cancel. Make one closed simple polygon visiting all six symbols exactly once. Turn only at symbols. No crossing, touching, passing through a third symbol or straight 180-degree turns. Triangles require an acute angle below 90 degrees, squares a right angle exactly 90, pentagons an obtuse angle between 90 and 180. Always use the smaller angle between the two links, even at inward bends. Any slope and link length is allowed. Twelve original unique six-point layouts on a 5x5 guide grid. Undo/reset/next/levels and saved loop palette/angle letters; shapes remain when letters are hidden.

## Download and status
https://mega.co.nz/#!tVkQyA5J!xJa28p0JC0U9ifoVe8vpUQTwc3a-BI2SvOyTnEQ6slM
APK SHA256 3e06d549edc0d51996b83b9aa7ff10664c6ea0b95ac562ce7c5184e31f01af29; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Independent oracle follows the cycle, uses Java2D Line2D segment intersection and point-on-segment tests, and classifies angles by the Pythagorean side-length relation, not production dot products. It agrees with production integer orientation, dot-product angle and graph checks on all 393,216 edge subsets across 12 boards plus 120,000 random/full-invalid masks. Exactly one solution per puzzle; all 12 point layouts distinct. Archived portable generator enumerates all 60 undirected Hamiltonian cycles per board and reproduces levels.json. Bounds, select/cancel, solved lock and solve/undo/replay/reset pass. Drawing adapter tests actual paired-symbol taps, selection ring/cancel/blank taps, reset/undo/next/levels/menu/settings/privacy and saved palette/angle letters/completion. Seven drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry and semantic review of all 157 prior studio cards found no Angle Loop match. Starstitch traverses fixed constellation edges exactly once, Branchvale flips cell diagonals, and Towercress draws orthogonal grid loops around towers. Anglewren instead chooses arbitrary straight links among symbols, checking geometric simplicity and acute/right/obtuse vertex angles. Known Angle Loop genre, not a global invention. This follows the shape-clue edition at https://maybepuzzles.com/types/angle-loop/ and https://madmahoganypuzzles.wordpress.com/2020/12/16/puzzle-24-angle-loop/ . The separate Inaba numeric exact-angle edition is not implemented. No source puzzle copied. Recovered repository corpus remains partial.

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated symbol positions, angle types and loops. javac -d /tmp/angle-test src/com/gg007/anglewren/Board.java BoardTest.java and java -cp /tmp/angle-test com.gg007.anglewren.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Anglewren runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Loop palette, angle letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/tugpr84k6v6x-anglewren-source-archive, including exact cumulative 158-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/anglewren holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
