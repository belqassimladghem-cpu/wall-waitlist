# Étude de marché & stratégie marketing low-budget — app type QUITTR
Date : 17 novembre 2026. Sources : ~40 recherches/pages Firecrawl (NY Mag, 404 Media, ASOitis, Screensdesign, Startup Spells, Trailblazer, Unhooked, Obex, Firstlight, AppGazers, RevenueCat, Whop, LinkedIn/AppKittie, Indie Hackers, YC, Christian Today…).

## 1. L'information n°1 : le leader a disparu
- QUITTR (Alex Slater & Connor McLaren, lancé août 2024, construit en 10 jours, 3 000 $ de budget initial) a atteint ~250 k$/mois en 4 mois, 500 k$+/mois et 1,5 M de téléchargements déclarés en mars 2026, ~1 M d'utilisateurs actifs mensuels (Sensor Tower).
- Mars 2026 : 404 Media révèle une base Firebase mal configurée exposant ~600 000 utilisateurs (âges, fréquence, confessions, >100 000 mineurs), alertée depuis des mois.
- Le fondateur quitte le poste de CEO à 20 ans (désaccord cofondateur). Dernière mise à jour 23 juin 2026. Revenus estimés : 80 k$/mois en août, ~20-25 k$/mois en octobre. Sentiment des avis écrits : 78,6 % négatif malgré 4,7★.
- Fin septembre : communauté in-app disparue, demandes de remboursement. 31 octobre 2026 : QUITTR retiré de l'App Store et de Google Play, sans explication.
=> Il y a aujourd'hui un trou de ~1 M d'utilisateurs actifs orphelins et une marque brûlée sur la confiance. C'est la fenêtre.

## 2. Carte du marché (prix vérifiés août-oct 2026, revenus = estimations tierces à prendre avec prudence)
| App | Positionnement | Prix | Revenus estimés | Canal principal |
|---|---|---|---|---|
| QUITTR (retiré) | Gamifié, panic button, IA "Melius", communauté, blocker | 9,99-14,99 $/mois, 19,99-29,99 $/an, 49,99 $ lifetime, hard paywall | 500 k$/mois (pic) -> ~20 k$ (oct 2026) | Créateurs payés au CPM, Meta ads, SEO |
| Brainbuddy (2013) | Programme 100 jours, Life Tree, blocker | ~13 $/mois, ~100-120 $/an | Android 14-68 k$/mois, iOS <5 k$ (AppGazers) | Ancienneté/ASO, quasi zéro marketing |
| Fortify (FTND) | Éducation, "lifestyle change", allies, télé-thérapie, tier gratuit | 12 $/mois, 90-120 $/an, 200 $ lifetime | n/a (3,7★ Play, bugs) | Réseau Fight The New Drug, YouTube |
| Relay (YC S22) | Groupes de 3-8 pairs, programme 16 semaines par thérapeutes, Zoom | 11,99 $/mois, ~150 $/an, essai 30 j, garantie 30 j | n/a (4,9★, 50K+ Play) | Affiliés (Ed Latimore…), podcasts, YC |
| Unchaind | Chrétien, compagnon IA biblique, groupes | abonnement | iOS 28-228 k$/mois, Android 19-92 k$/mois ; 500 k DL en <1 an ; racheté par Rocapine (13 M$ levés) | TikTok créateurs chrétiens |
| BlockerX | Blocker multi-devices, panic switch, partenaire | 1,99 $/sem -> 150 $ lifetime | Android 17-82 k$/mois | ASO "blocker", Chrome |
| Covenant Eyes (2000) | Accountability screenshots, églises | 18 $/mois, 198 $/an | n/a | B2B églises, institutions |
| Seed | Gamifié (orbes 3D), no-nut | in-app | Android 6-17 k$/mois | TikTok |
| Nouveaux 2026 : Sever (free-to-start), Firstlight (iPhone, sans compte, privacy), Obex (chrétien iPhone), Unhooked (offline, lancement), Ascension, Get a Grip (IA coach), Mend, Rewire (Android), WINNR (FR, 9 €/mois, 49 €/an), NoBeep (FR) | Tous attaquent le vide laissé par QUITTR, souvent sur la **confidentialité** | | | Blogs comparatifs SEO + TikTok |

Marché FR : quasi vide. WINNR et NoBeep existent, aucun n'a de marque. Créateurs FR nofap présents (ex. @rebootmental.fr). Les listings App Store ne sont qu'en EN/ES chez QUITTR : les autres langues étaient "de la portée laissée sur la table".

## 3. Comment QUITTR a fait autant d'argent (le playbook exact)
### 3.1 Onboarding = la machine à cash (CVR 25 % download->payant, 99 % finissent le quiz)
35-40 écrans, ~2 min 50 : 
1. "Let's find out if you have a problem" -> carte membre holographique avec "streak 0 jour" (l'utilisateur possède un objet avant de donner quoi que ce soit).
2. Quiz 10-12 questions numérotées (fréquence, escalade, depuis quand…) + "Où nous as-tu connus ?" (Instagram/TikTok/X/Facebook/Google/Thérapeute) = attribution gratuite.
3. Écran "Analyse… 64 % vs moyenne 40 %" (toujours le même score).
4. Checklist de symptômes (mental/physique/social/foi) -> l'utilisateur décrit son problème avec les mots de l'app.
5. 5 slides éducation ("Porn is a drug"…), logos presse, citations Huberman/Bartlett, graphique "avec/sans", "1 000 000+ ont choisi la liberté".
6. Objectifs, prompt ATT, prompt de notation Apple AVANT usage.
7. "Signe pour t'engager" (signature au doigt) + plan personnalisé + **date de quit calculée** ("Tu seras libre le 4 janv. 2027").
8. Paywall en 3 couches : offre unique -80 % avec compte à rebours 5 min -> page de vente (bénéfices, témoignages, "Purchase appears Discretely") -> essai 3 jours / annuel présélectionné / lifetime. Copy "60 % off, 9 places restantes". Bouton "Become a QUITTR".
Ils ont testé le freemium : "quand c'est gratuit, personne ne l'utilise". Hard paywall + annuel 30-45 $ = le sweet spot. Stack : Swift, Firebase, Mixpanel (2 % de drop par écran), Superwall (QUITTR est devenu un template Superwall), Figma (copies d'écran des onboardings d'apps à 5-6 M$).

### 3.2 Acquisition = créateurs payés à la vue, réinvestissement total
- 3 000 $ -> 37 000 $ le premier mois, tout réinvesti ("transformer 1 $ en 4 $").
- Niches ciblées dans l'ordre : chrétiens ("c'est contre Dieu"), fitness ("low T"), self-improvement/red-pill ("semen retention"). Un appel à 50 $ avec un créateur chrétien = 1 000 $/jour.
- Modèle de paiement : CPM 2-3 $ / 1 000 vues (1 M de vues ≈ 2 000-3 000 $), 20 % d'avance, le reste après versement Apple ; garantie de vues ("1 500 $ pour 500 000 vues, sinon prorata ou repost") ; retainers 2-10 k$ ; bonus 500 $ à 500 k vues. Un créateur à 2 M d'abonnés : vidéo à 9,9 M de vues = 40 k$ en 1 jour, 100 k$ en 65 h.
- Outreach : DM/mail/appel depuis un compte vérifié, message "Paid promo for Quittr, helped 100,000+ users", jamais de prix par écrit, VA Fiverr pour les DMs, Google Sheets, Growi pour les contrats, objectif "2 000 DMs".
- Contrat : montrer l'app dans la vidéo, droits d'usage pour la rediffuser en ads.
- Brief créatif (page UGC Army) : être "relatable" (rechute à répétition), s'inspirer d'autres apps (vidéo copiée de Finch), angle chrétien en story, **montrer la démo de l'app très tôt** et rester court.
- "UGC Army" : 10 % des revenus générés par tes vidéos (rev-share, zéro cash d'avance). Programme de parrainage in-app avec code promo rémunéré.
- Posting organique multi-comptes quotidien + tests créas Meta constants (40 k$/mois à 3-4x ROAS au pic).
- SEO/LLM-SEO (agence Trailblazer, à partir de mars 2025) : 0 -> 24,7 k clics / 910 k impressions en 6 mois, ~1 500 $/jour de revenus organiques, grâce à des articles "QUITTR vs X", "Best X alternatives", "Comment désactiver le contenu sensible sur X" + présence ChatGPT/Perplexity.
- Coups de pub : Oprah, NY Mag, Theo Von visé, "Quittr rachète PornHub" (stunt).

### 3.3 Contrainte structurelle : l'App Store ne retourne AUCUNE app pour "quit porn", "porn blocker", "porn addiction", "stop porn" (vérifié oct. 2026). Les seuls mots-clés qui marchent : "nofap" (QUITTR #1), "self control", "quit", "addiction recovery", "dopamine detox" (popularité 20, difficulté 17, leader avec 23 notes = porte ouverte). => La marque doit devenir la recherche ("quittr" popularité 60). Il faut un nom qu'on peut taper.

### 3.4 Pourquoi ça s'est effondré (tes leçons)
Sécurité des données (Firebase ouvert, alertes ignorées) ; promesses non étayées (chiffres incohérents 1 M / 1,5 M / 2 M, "76 % plus vite", "64 % plus dépendant") ; honte comme moteur initial ("gay", "losers") ; achats lifetime perdus après mise à jour (entitlement lié au compte serveur, pas au reçu Apple) ; support absent ; fondateur parti vers un autre projet ; produit "excellent les 10 premières minutes, vide après" (critique commune à toute la catégorie, Obex/Firstlight). Chez Relay à l'inverse : vidéo du fondateur à l'inscription, appel 15 min semaine 1, garantie 30 jours.

## 4. Espaces blancs (où te positionner)
1. **Confiance & vie privée** : "Zéro compte, zéro email, données sur l'appareil, chiffrées". C'est l'angle que Firstlight/Unhooked prennent, mais aucune app grand public ne le porte avec une marque forte. Après le scandale QUITTR c'est l'argument n°1.
2. **Francophone** : aucun leader FR/BE/CH/Québec/Afrique francophone. Localise (FR + EN + ES), les créateurs FR sont moins chers.
3. **Le moment de l'urge** (pas seulement le compteur) : panic button + plan "les 5 prochaines minutes" + rechute traitée comme une donnée, pas une honte (Fortify : "a lapse is not a relapse").
4. **Lifetime fiable** et restauration via reçu store : 1 ligne de marketing gratuite face aux plaintes QUITTR.
5. Niche de départ : chrétiens (Unchaind a prouvé 500 k DL en <1 an) OU fitness/discipline. Choisis-en UNE pour les 90 premiers jours.

## 5. Stratégie 90 jours, budget mini, PC faible
### Principe
Le PC faible n'est pas un problème : tout le contenu se fait sur **téléphone** (CapCut mobile, enregistrement d'écran natif) ou dans le navigateur (Canva, CapCut Web, ElevenLabs, ChatGPT). Pas de montage lourd, pas de rendu 4K.

### Phase 0 (semaines 1-2) — fondations
- Nom court, unique, tapable, achetable en .app/.com et libre sur TikTok/IG/YT.
- Landing 1 page (Framer/Carrd gratuit) + waitlist + 3 pages SEO : "Meilleures apps pour arrêter le porno 2027", "Alternative à QUITTR", "QUITTR a disparu : que faire".
- Stores : titre + sous-titre avec "dopamine detox", "self control", "nofap", "addiction recovery". Fiches en FR, EN, ES. Screenshots = les 3 premiers vendent (panic button, streak, privacy).
- Monétisation : hard paywall après quiz, annuel présélectionné (≈29-39 €), mensuel 9,99 €, lifetime ≈59-79 €, essai 3 jours à A/B tester (RevenueCat 2026 : hard paywall convertit 10,7 % vs 2,1 % freemium ; Health & Fitness avec essai convertit 37,7 % essai->payant). RevenueCat/Adapty/Superwall ont des tiers gratuits.
- Quiz onboarding 10-12 questions + score + date de liberté + signature + "Où nous as-tu connus" (attribution gratuite).
- Sécurité : règles Firebase/Supabase RLS verrouillées, audit avant lancement, politique de confidentialité claire. C'est ton marketing.

### Phase 1 (semaines 2-8) — machine de contenu organique (coût ≈ 0)
Comptes : 1 compte marque + 2 comptes "persona" (ex. "mon journal jour 1 -> 90", et un compte faceless éducation), sur TikTok, Reels, Shorts simultanément. 1 téléphone = max 3 comptes propres, ne jamais poster en rafale identique (shadowban).
Cadence : 2-3 posts/jour/compte. Volume > perfection ; chaque post est un test de hook.
Formats qui marchent dans la niche (ordre de rendement/effort) :
1. **Slideshow TikTok/carrousel** (Canva, 5-8 slides) : "Jour 1 vs Jour 30 sans porno", "7 signes que ton cerveau est frit", "Ce que j'aurais aimé savoir avant d'arrêter". Zéro caméra, 10 min/post, haute sauvegarde.
2. **Démo d'écran 7-15 s** : enregistrement du panic button / de la date de liberté / du quiz, texte en overlay, son tendance. QUITTR dit que ses meilleures ads montrent l'app dans les 2 premières secondes.
3. **Story relatable en texte sur fond** (voix ElevenLabs gratuite ou TikTok TTS) : "J'ai rechuté 47 fois…", angle chrétien en storytelling.
4. **Réactions à des stats / clips Huberman** (fair use court, commentaire à valeur ajoutée).
5. **Build in public** : "J'ai construit une app pour arrêter le porno, voilà le jour 12" (très fort sur X, LinkedIn, r/SideProject, r/EntrepreneurRideAlong, Indie Hackers).
10 hooks à tester : "Si tu regardes du porno tous les jours, regarde ça 10 s" / "Ton cerveau après 90 jours sans porno" / "Le bouton rouge qui m'a sauvé à 2 h du matin" / "QUITTR a disparu, voilà ce que j'utilise" / "Personne ne te dit ça sur la rechute" / "Jour 1 : j'ai signé ça" / "L'app qui ne connaît même pas ton email" / "3 h de sommeil en plus, voilà pourquoi" / "Ce que 600 000 gars ont appris à leurs dépens (fuite de données)" / "Fais le test en 60 s".
Reddit : r/NoFap interdit toute promo (ban). Fais de la valeur pure (comptes rendus, guides) sur r/pornfree, r/PornAddiction, r/getdisciplined ; promo uniquement sur r/SideProject, r/iosapps, r/androidapps, r/EntrepreneurRideAlong, et réponds aux threads "quelle app ?" avec comparatifs honnêtes.
YouTube long : 1 vidéo/semaine "comment j'ai construit…" ou "meilleures apps 2027 comparées" (SEO durable, YouTube est cité par les IA).

### Phase 2 (semaines 4-12) — créateurs payés sans se ruiner (300-1 000 €)
1. **Whop Content Rewards / clipping** : crée une campagne à 1-2 $ / 1 000 vues, budget 300-500 $, brief = "montre l'app en 2 s, hook sur la rechute/la discipline, lien en bio". Des dizaines de clippers postent pour toi. Attention aux vues bots : plafonne par post, paie sur vues vérifiées, regarde le médian (si <1 000 vues médianes, change de format).
2. **Micro-créateurs FR/EN (10-50 k abonnés, niche chrétienne/fitness/discipline)** : TikTok se paie 25-200 $ par vidéo à ce niveau ; propose le modèle QUITTR : 20 % d'avance + 2-3 $ / 1 000 vues avec garantie de vues, ou **rev-share 10-20 % via code promo** (zéro cash). Script DM : "Promo payée pour [App], l'app pour arrêter le porno sans donner ton email. Tu fais ~X vues/vidéo : 4 vidéos, Y vues garanties, Z €. Un appel de 10 min ?". Jamais de prix par écrit, appel pour closer. Objectif : 100 DMs/semaine (VA Fiverr à 5 $/h si besoin).
3. **Droits d'usage** systématiques pour rediffuser les meilleures vidéos en Spark Ads.
4. Équity/rev-share long terme avec 1-2 créateurs qui convertissent (modèle STOPPR, clone FR de QUITTR : 5 k$ en 2 semaines sur 2 vidéos virales).

### Phase 3 (dès qu'un post organique convertit) — paid minimal
- TikTok Spark Ads sur les 2-3 posts organiques qui ont converti, 10-20 €/jour, 1 campagne test + 1 campagne scale, pas de ciblage d'intérêts (cible par la créa). Benchmarks : CPI ≈ 1 € en Europe sur TikTok, Health & Fitness median CPI 3,77 $ ; vise un payback < 30 jours.
- Meta : angle conforme ("discipline", "dopamine", "concentration", "reprends le contrôle"), zéro nudité/vulgarité, pas "addiction treatment" aux US sans certification LegitScript. Teste 5 créas/semaine, coupe à 2x le CPA cible.
- Apple Search Ads sur "nofap", "dopamine detox", "self control", "quittr" (CPI médian 0,51 $ hors US).
- Outils IA UGC (Creatify 10-39 $/mois, Arcads) seulement pour tester des hooks en paid, jamais présentés comme vrais témoignages.

### Phase 4 (continu) — SEO/GEO gratuit
Blog sur ton site : "X vs Y", "Alternatives à [chaque concurrent]", "App gratuite pour arrêter le porno", "Comment bloquer le porno sur iPhone/Android", en FR et EN. Cite des sources (JMIR 2022 : aucune app n'a de preuve d'efficacité -> sois honnête, ça te distingue). Objectif : être cité par ChatGPT/Perplexity quand on demande "meilleure app pour arrêter le porno". QUITTR a tiré 1 500 $/jour de ce canal.

### Budget 90 jours (indicatif)
| Poste | Coût |
|---|---|
| Domaine + landing (Framer/Carrd free) | 15 € |
| Apple Developer | 99 €/an |
| Canva free / CapCut mobile / ElevenLabs free / ChatGPT | 0-20 €/mois |
| Whop clipping | 300-500 € |
| 3-5 micro-créateurs (CPM/rev-share) | 200-500 € |
| Spark Ads tests | 300 € |
| Total | ≈ 1 000-1 500 € |

### KPIs à suivre dès le jour 0
Vues médianes par post (>1 000 = format OK), taux quiz terminé (>90 %), download->payant (>8 % hard paywall), CPA payant par créateur (<15 €), rétention J30, sentiment des avis écrits (pas seulement les étoiles), remboursements (<6 %).

## 6. Erreurs à ne pas reproduire
Honte comme levier, chiffres inventés, prompt de notation avant usage, deux remises contradictoires, scarcity bidon ("9 places"), lifetime sans restauration store, base de données ouverte, 2 langues seulement, dépendance à un seul créateur, abandon du support.

---

## 7. Mise à jour : plan d'acquisition à 50 €/jour (≈1 500 €/mois) — objectif "le plus de clients, le plus vite"

### Répartition du budget (mois 1 -> mois 3)
| Canal | Mois 1 (test) | Mois 2-3 (scale) | Pourquoi |
|---|---|---|---|
| Créateurs micro FR/EN au CPM (2-3 $/1 000 vues, 20 % d'avance, vues garanties) | 600 € | 700-900 € | Le canal qui a fait QUITTR, Cal AI, Unchaind. Le seul qui crée la recherche de marque. |
| Clipping Whop (1-2 $/1 000 vues) | 250 € | 200 € | Volume de vues pas cher pour tester 30-50 hooks en parallèle. |
| TikTok Spark Ads sur les posts gagnants | 300 € | 400-600 € | Tu n'achètes que ce qui a déjà converti en organique. |
| Apple Search Ads ("nofap", "dopamine detox", "self control", "quittr", "brainbuddy") | 150 € | 200 € | Intent pur, CPI médian 0,5-2,5 $, QUITTR a disparu de ces résultats. |
| Outils (Canva Pro, CapCut Pro, ElevenLabs, PostHog gratuit) | 60 € | 60 € | |
| Réserve pour doubler un créateur qui explose | 140 € | reste | Règle QUITTR : "quand ça pop, tu remets dessus". |

### Séquence jour par jour (30 premiers jours)
- J1-J3 : landing en ligne (ce dépôt), Apps Script branché, PostHog branché, 3 comptes TikTok/IG/Shorts créés et "chauffés" (regarder la niche 20 min/jour, pas de post).
- J1-J7 : 50 DMs/jour à des micro-créateurs (10-80 k abonnés, niches : chrétiens FR/EN, fitness, discipline, "mindset", témoignages nofap). Script dans la section 5. Objectif : 5 deals signés semaine 1, 10 vidéos publiées semaine 2.
- J4 : lancement du posting organique : 2-3 posts/jour/compte, 60 % slideshows, 30 % démo d'écran du quiz/carte, 10 % build in public. Lien en bio = landing avec `?test=1` (ouvre le quiz direct).
- J5 : campagne Whop Content Rewards 250 $ à 1,5 $/1 000 vues, brief = "l'écran de la date de liberté dans les 2 premières secondes".
- J10 : premiers Spark Ads (10-15 €/jour) sur les 3 posts avec le meilleur ratio clics-bio/vues.
- J14 : Apple Search Ads 5 €/jour sur les 5 mots-clés ci-dessus (même avant la sortie, pour mesurer le CPI et préchauffer la fiche en attente ? non : seulement une fois l'app en TestFlight/Store ; d'ici là, 100 % vers la landing).
- J21 : bilan, on coupe tout ce qui a un coût par inscrit > 2 € et on remet le budget sur le top 2.
- J30 : objectif réaliste 3 000-8 000 inscrits waitlist à 0,3-1 € l'inscrit, et 2-3 créateurs à relancer en rev-share.

### Le PC (Ryzen 7 6000) change une chose : tu peux produire des vidéos "premium" localement
- CapCut Desktop et DaVinci Resolve (gratuit) tournent sans problème : démos d'écran 1080p60, sous-titres animés, zooms.
- Remotion (React) : un template vidéo paramétré par date/score qui génère automatiquement 100 variantes de la "carte de liberté" (prénoms, dates, hooks) pour les tests Spark Ads. C'est le levier "volume de créas" que QUITTR payait à des éditeurs.
- Pas besoin de GPU pour ça. Évite seulement la génération vidéo IA locale (Wan, etc.) : passe par Creatify/Arcads si tu veux tester des avatars.

### Métriques cibles pour que 50 €/jour soit rentable
Coût par inscrit waitlist < 1 € ; taux quiz terminé > 85 % ; email -> installation au lancement > 35 % ; installation -> payant (hard paywall) > 8 % ; donc coût par payant ≈ 30-35 € contre un panier annuel 29 € + lifetime/renouvellements : payback < 12 mois en mois 1, < 3 mois dès que l'organique prend le relais. Si le coût par inscrit dépasse 2 € après 300 € dépensés sur un canal, coupe.

## 8. Déploiement de la landing (index.html)
1. Crée une Google Sheet, Extensions > Apps Script, colle le `doPost` du commentaire en haut de `index.html`, Déployer > Application web > accès "Tout le monde", copie l'URL dans `CONFIG.GAS_URL`.
2. Remplace `CONFIG.BRAND` par ton nom, `FOUNDER_CAP`, l'email de contact, et ajoute une clé PostHog EU si tu veux l'entonnoir (événements : page_view, quiz_opened, quiz_answer, quiz_result, pledge, lead_submitted, lead_success, share_copied).
3. Héberge en 1 clic : Vercel/Netlify (drag & drop du dossier) ou GitHub Pages sur ce dépôt. Domaine court.
4. Lien en bio : `https://ton-domaine/?test=1` (ouvre le quiz immédiatement). Liens créateurs : `?ref=nomducreateur` (stocké dans la Sheet pour l'attribution).
