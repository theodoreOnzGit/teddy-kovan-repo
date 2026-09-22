# teddy-kovan-repo

Theodore Ong's [Kovan](https://github.com/theodoreOnzGit/outram-park-backend/tree/develop/crates/kovan)
folder: the research knowledge layer (papers, topics, projects and their
connections, as TOML and Markdown) built on top of Kovan's built-in
nuclear-engineering map.

## Layout

| Path | What |
|---|---|
| `kovan_root.toml` | This Kovan folder's settings, including where its two corpora come from |
| `papers/`, `topics/`, `projects/` | Research records, one folder each, as TOML and Markdown |
| `bibliography.bib` | The folder's BibTeX, one entry per paper |
| `literature/standard-corpus/` | **Submodule:** Kovan's standard corpus, the same [`reactor-literature`](https://github.com/theodoreOnzGit/reactor-literature) repository every Kovan folder carries (branch `main`); Kovan hardcodes its `kovan-standard-open-corpus/` |
| `literature/open-corpus/` | **Submodule:** [`reactor-literature`](https://github.com/theodoreOnzGit/reactor-literature), the open corpus (public). Its `kovan-standard-open-corpus/` is what Kovan hardcodes; `theodore-open-corpus/` is the owner's other open literature |
| `literature/proprietary/` | **Submodule:** the proprietary corpus, a **private** repository. Only people with access to it can fetch it; for everyone else it stays empty |

## Getting it

```bash
git clone --recurse-submodules https://github.com/theodoreOnzGit/teddy-kovan-repo.git
```

or, after a plain clone, `git submodule update --init`. Without access to the
private repository, fetch just the open corpora with
`git submodule update --init literature/open-corpus literature/standard-corpus`.

Open the folder in Kovan (Home → ⚙ Set up repositories…, or Home → Open Kovan Folder).

## Rules

- Nothing without a verified redistribution licence goes into this repository
  or the open corpus; it belongs in the private proprietary corpus.
- `kovan_root.toml` holds repository URLs only, never a password or token.
