# 99.9 SCORE — premye vèsyon Android

Sa a se yon pwojè demaraj Android Studio pou aplikasyon foutbòl **99.9 SCORE**.

## Sa ki ladan l
- Entèfas mobil ble/nwa ki mache ak logo ou te bay la.
- Paj prensipal ak onglet Jodi a, An dirèk, Ap vini.
- Kat match ak nòt demonstrasyon.

## Enpòtan
Nòt ki parèt yo se **egzanp sèlman**. Aplikasyon sa a poko konekte ak yon sèvis done foutbòl, kidonk li pa bay rezilta an dirèk ankò. Pou mete vrè rezilta, fòk nou chwazi yon API foutbòl, jwenn kle API a, epi konekte li ak aplikasyon an.

## Louvri pwojè a
1. Enstale Android Studio sou òdinatè.
2. Debake fichye ZIP la.
3. Nan Android Studio, chwazi **Open** epi chwazi dosye `999_score_android`.
4. Kite Gradle fè Sync.
5. Kouri aplikasyon an sou yon telefòn Android oswa yon emulator.

## Kreye APK
Nan Android Studio: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

APK debug la ap parèt nòmalman nan:
`app/build/outputs/apk/debug/app-debug.apk`

## Pwochen etap
- Mete imaj logo a kòm icône aplikasyon an.
- Chwazi yon founisè done foutbòl/API.
- Konekte rezilta an dirèk, kalandriye, klasman, estatistik ak notifikasyon.

## Konpile APK sou GitHub san òdinatè
1. Kreye yon nouvo repository GitHub ki rele `999-score`.
2. Sou paj repository a, chwazi **Add file > Upload files**.
3. Debake ZIP pwojè a anvan upload; mete tout fichye/dosye ki anndan pwojè a nan repository a, tankou dosye `.github`.
4. Fè **Commit changes** sou branch `main`.
5. Ale nan tab **Actions**, chwazi workflow **Build 99.9 SCORE APK**, epi peze **Run workflow** si li pa kòmanse otomatikman.
6. Lè li fini avèk siksè, louvri rezilta workflow la epi telechaje artifact `999-score-debug-apk`.
