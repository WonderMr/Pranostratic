# Pranostratic

A single XMind mind map, `origin.of.languages.xmind`, that lays out a genealogical tree of the
world's language families under the hypothetical Nostratic (Pra-Nostratic / Borean) macrofamily.
Node labels are in Russian; extinct languages are marked with `†` and uncertain groupings with
`?`. Status: personal research notes, edited between 2018-02-08 and 2018-02-23, inactive since.

## Layout

- `origin.of.languages.xmind`: the mind map (about 4.3 MB; XMind 3 format, a ZIP archive).
  - `content.xml`: the current tree (one sheet, about 1,100 topics).
  - `meta.xml`, `styles.xml`: metadata and styles.
  - `Revisions/`: XMind's own revision history snapshots.
- `README.md`: project overview.

Top of the tree: Western Nostratic (Afroasiatic, Indo-European, Kartvelian) and Eastern Nostratic
(Altaic, Dravidian, Uralic, Eskimo-Aleut), each expanded down to individual languages and dialects.

## Setup / Build / Run / Test

- Open the file in XMind. Nothing is built or tested.
- To read or diff the tree without XMind, list or extract `content.xml` from the archive
  (read-only):

  ```sh
  unzip -l origin.of.languages.xmind
  unzip -p origin.of.languages.xmind content.xml
  ```

## Conventions

- Content language: Russian (keep new labels in Russian). Separate alternative names with `/`.
- Default branch: `master`. Commit messages are short, in English or Russian ("today's work",
  "Сегодняшняя работа").

## Gotchas and boundaries

- The file is binary for Git: each commit stores a full new copy and diffs are not readable.
  Edit it in XMind; hand-editing the XML inside the archive is error-prone, so do it only when asked.
- The tree reflects one reading of a contested hypothesis; do not present it as consensus
  classification.
