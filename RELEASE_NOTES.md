Desktop application for preparing Canadian SR&ED claims, in English or French.
Application de bureau pour préparer les demandes de RS&DE, en français ou en anglais.

**Download page / Page de téléchargement : https://blog.rdinnovate.com/workbench-canada/**

### 1.0.0 — first release

- Federal SR&ED for corporations, individuals and partnerships: T661 (all parts, including the
  capital and lease lines for tax years beginning after 15 December 2024), Schedule 31 or
  T2038(IND), and the T5013 allocation. Both rule sets are built in: tax years beginning before
  16 December 2024 and after.
- Every province and territory with an R&D credit: Ontario (OITC, ORDTC, OBRITC), British
  Columbia, Saskatchewan, Manitoba, New Brunswick, Nova Scotia, Newfoundland and Labrador, Yukon,
  the Alberta Innovation Employment Grant and the Quebec CRIC.
- Special forms when the facts apply: Schedule 49, T1174, T1263, T1145, T1146, AT4970,
  RD-1029.8.EN and RD-1029.8.PR.
- Unsettled points are shown as positions you decide, with the source for each.
- AI help to set up projects and draft T661 Part 2 (lines 242, 244 and 246) from your own notes.
- The whole app, the downloads and the licence are available in English and in French.

### 1.0.0 — première version

- RS&DE fédérale pour les sociétés, les particuliers et les sociétés de personnes : T661 (toutes
  les parties, y compris les lignes de capital et de location pour les années d'imposition
  commençant après le 15 décembre 2024), annexe 31 ou T2038(IND), et répartition T5013. Les deux
  régimes sont intégrés : années commençant avant le 16 décembre 2024 et après.
- Chaque province et territoire offrant un crédit de R-D : Ontario (CIIO, CIORD, CIOEPIR),
  Colombie-Britannique, Saskatchewan, Manitoba, Nouveau-Brunswick, Nouvelle-Écosse,
  Terre-Neuve-et-Labrador, Yukon, la subvention de l'Alberta pour l'emploi en innovation et le
  CRIC du Québec.
- Formulaires particuliers au besoin : annexe 49, T1174, T1263, T1145, T1146, AT4970,
  RD-1029.8.EN et RD-1029.8.PR.
- Les points non tranchés sont présentés comme des positions que vous choisissez, avec la source.
- Aide de l'IA pour structurer les projets et rédiger la partie 2 du T661 (lignes 242, 244 et 246)
  à partir de vos propres notes.
- L'application, les documents téléchargés et la licence sont offerts en français et en anglais.

### Which file / Quel fichier
| Platform / Plateforme | File / Fichier |
|---|---|
| macOS, Apple silicon (M1–M4) | `RnD-Tax-Workbench-Canada-1.0.0-mac-arm64.dmg` |
| macOS, Intel | `RnD-Tax-Workbench-Canada-1.0.0-mac-x64.dmg` |
| Windows 10/11, 64-bit | `RnD-Tax-Workbench-Canada-1.0.0-win-x64.exe` |
| Linux, 64-bit | `RnD-Tax-Workbench-Canada-1.0.0-x86_64.AppImage` or the `.deb` |

The `.zip`, `.blockmap` and `.yml` files are used by automatic updates.
Les fichiers `.zip`, `.blockmap` et `.yml` servent aux mises à jour automatiques.

### Signing / Signature
The macOS builds are signed and notarised by Apple. The Windows installer is not yet code-signed:
Windows SmartScreen shows a warning; choose **More info**, then **Run anyway**.
Les versions macOS sont signées et notariées par Apple. L'installateur Windows n'est pas encore
signé : SmartScreen affiche un avertissement; choisissez **Informations complémentaires**, puis
**Exécuter quand même**.

### Verifying / Vérification
Checksums are in `SHA256SUMS.txt`. macOS and Linux: `shasum -a 256 <file>`.
Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`

### Your data / Vos données
Claim data is stored in a local database on your own computer. Only what an AI step needs is sent
for processing: by Amazon Web Services in Canada (Canada Central and Canada West), with Anthropic's
Claude API in the United States as a fallback, under the AI data processing terms you accept when
the app first starts. Your sign-in email and credit records are held by Amazon Web Services in
Australia.

Les données des demandes sont conservées dans une base de données locale sur votre ordinateur.
Seul ce dont une étape d'IA a besoin est envoyé pour traitement : par Amazon Web Services au Canada
(Canada Centre et Canada Ouest), avec l'API Claude d'Anthropic aux États-Unis en secours, selon les
conditions de traitement des données par l'IA acceptées au premier démarrage. Votre courriel de
connexion et vos achats de crédits sont conservés par Amazon Web Services en Australie.

Support / Soutien : rd@rdinnovate.com
