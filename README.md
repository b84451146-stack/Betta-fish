# Betta fish in ASCII

An animated ASCII betta fish that grows from a spark, with your name written underneath.

## Change the name
Open `index.html` and edit the line near the top:

    const NAME = new URLSearchParams(location.search).get('name') || 'KOUSHIK';

Replace `KOUSHIK` with any name. You can also share a link ending in `?name=Anything`.

## Put it online (GitHub Pages)
1. Upload `index.html` (and this README) to a new GitHub repository.
2. Go to Settings > Pages, set Source to "Deploy from a branch", pick `main` and `/ (root)`, and Save.
3. After a minute your link appears: `https://<username>.github.io/<repo>/`
