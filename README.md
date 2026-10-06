# CoBPE project website

Static project page for **More Than Words: Compositional Tokenization for Efficient Language Models** (Reif, Kaplan, Schwartz; COLM 2026), served at <https://co-bpe.github.io>.

- Paper: <https://arxiv.org/abs/2610.05597>
- Code: <https://github.com/schwartz-lab-NLP/cobpe>

The page is plain HTML and CSS (`index.html`, `style.css`), with no build step. The token examples, method diagram and result charts are drawn in HTML/SVG in the poster's colors, so text stays sharp and editable; `images/main_example.png` (the paper's Figure 1) is used only as the link-preview image.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## When the models are released

Replace the two "coming soon" placeholders in `index.html` (the **Models** button in the header and the sentence under "Code and models") with links to the weights.
