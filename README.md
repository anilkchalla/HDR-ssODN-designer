# CRISPR HDR ssODN Designer

A single-file, browser-based tool to design asymmetric single-stranded oligodeoxynucleotide
(ssODN) donors for CRISPR homology-directed repair (HDR), following the
[Addgene / Richardson *et al.* 2016](https://blog.addgene.org/optimizing-donor-dna-for-enhanced-crispr-genome-editing)
guidelines (127 nt total; asymmetric 91 nt PAM-proximal + 36 nt PAM-distal arms; complementary to the non-target strand).

**▶ Live tool:** `https://anilkchalla.github.io/HDR-ssODN-designer/index.html`

## Features

- Locates the protospacer + PAM on either strand and computes the SpCas9 blunt cut site (3 bp 5′ of the PAM).
- Designs an asymmetric ssODN with arms **fixed** at the canonical 91/36 nt of homology (never auto-extended).
- **Multiple edits per design** — substitution, insertion, deletion, or paste-a-sequence *find → replace*.
- Flags re-cutting risk and **suggests** (does not auto-apply) PAM/seed blocking mutations; optional
  synonymous/silent check for coding regions.
- Output is **case- and color-coded** (lowercase = homology arms, UPPERCASE = edited bases) with a
  schematic, a base-level view around the cut, and a plain-English explanation.
- Runs **100% in your browser** — no install, no server, and no sequence data ever leaves your computer.

## Use

Open `index.html` in any modern browser — double-click the local file, or visit the hosted link
above. Click **Load example** for a worked design.

## Method / citation

Richardson C.D., Ray G.J., DeWitt M.A., Curie G.L., Corn J.E.
*Enhancing homology-directed genome editing by catalytically active and inactive CRISPR-Cas9 using
asymmetric donor DNA.* **Nat Biotechnol** 34, 339–344 (2016).

## Disclaimer

For research use. Always sanity-check the design against your own sequence and confirm edits by sequencing.

## License

No license is set yet (default = all rights reserved). To let others reuse it, add a `LICENSE` file —
[MIT](https://choosealicense.com/licenses/mit/) is a common permissive choice.
