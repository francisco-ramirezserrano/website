# franciscoramirezserrano.com

Personal website of Francisco Ramirez Serrano, served with GitHub Pages.

- `index.html`: home, About me and Writing (one page, five languages)
- `post.html`: the page that shows a single blog post
- `posts/`: blog posts, one Markdown file each
- `img/`, `media/`: photos, videos and figures
- `js/marked.min.js`: Markdown renderer (marked v12.0.2, MIT License)
- `Francisco_Ramirez_Serrano_CV.pdf`: web version of the CV (no phone number)
- `CNAME`: custom domain for GitHub Pages

## Writing a post

1. Edit (or create) `posts/<slug>.md`. The first line is the title: `# My title`.
2. While the file contains the line `<!-- draft ... -->`, the site shows "I'm still writing this one."
   Delete that line to publish the post.
3. Optional translations: add `posts/<slug>.es.md`, `.fr.md`, `.it.md` or `.de.md`.
   Without one, visitors in that language see the English text with a short note.
4. Link to a post with `post.html#<slug>`, e.g. https://franciscoramirezserrano.com/post.html#how-i-have-fun
