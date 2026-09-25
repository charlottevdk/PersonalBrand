# Opnamescript — persoonlijke video (60–90 seconden)

Dit script is voor de verplichte persoonlijke video op je personal-brand-website
(PB10-eis: "persoonlijk filmpje"). Houd het kort, natuurlijk en in één take als dat lukt.
Je kunt het in het Nederlands of Engels opnemen — kies de taal waarin je het meest
natuurlijk overkomt.

## Structuur

### 0–10 sec — Intro
> "Hi, ik ben Charlotte van den Kerkhoff, laatstejaars Commerciële Economie aan de
> Hogeschool van Amsterdam."

### 10–35 sec — Wat ik doe
> "Ik werk op het snijvlak van analyse en communicatie: van data naar inzicht naar
> een commerciële aanbeveling. Tijdens mijn stage bij Stryker zette ik bijvoorbeeld
> zelfstandig een AI-adoptieproject op — dat was niet opgedragen, ik zag de kans,
> bouwde het en presenteerde het aan vijf landen."

### 35–60 sec — Waar ik heen wil
> "Na mijn afstuderen zoek ik een rol bij een internationale, data-gedreven
> organisatie — het liefst in MedTech of een andere complexe B2B-sector. Voor mij
> zijn purpose en performance allebei niet-onderhandelbaar."

### 60–90 sec — Call to action
> "Ben je benieuwd wat ik voor jouw organisatie kan betekenen? Neem contact met me
> op — ik ga graag het gesprek aan."

## Praktische opnametips

- **Telefoon horizontaal**, op ooghoogte (stapel boeken werkt prima als statief).
- **Daglicht**: ga met je gezicht naar een raam toe zitten, niet ervoor (geen tegenlicht).
- **Rustige achtergrond**: een effen muur of opgeruimde kamer; geen rommel in beeld.
- **Geluid**: neem op in een stille ruimte, telefoon niet te ver weg (armlengte is goed).
- **Eén take is ok**: kleine versprekingen maken het menselijk — niet 20 takes doen.
- **Kijk in de lens**, niet naar jezelf op het scherm. Glimlach bij de intro.
- **Ondertiteling toevoegen** na het opnemen (bijv. via CapCut of YouTube Studio) —
  veel recruiters kijken eerst zonder geluid.
- Exporteer als **MP4** en noem het bestand `personal-video.mp4`.

## Op de website zetten

1. Zet `personal-video.mp4` in de repo-root (naast `index.html`).
2. Open `index.html` en zoek naar `<!-- VIDEO -->`.
3. Vervang de `.video-frame` div door het snippet uit de HTML-comment die erboven staat:
   `<video controls preload="metadata" src="personal-video.mp4" style="width:100%;border-radius:16px"></video>`
4. Commit en push — de video staat dan op de site.
