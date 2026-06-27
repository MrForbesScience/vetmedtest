# Veterinary MCQ Practice

A static multiple-choice quiz webpage for veterinary medicine revision.

The quiz now uses short clinical cases. Each category has a 30-case bank. A quiz attempt draws 5 cases from that bank, and each case has 4 linked MCQs.

Categories included:

- Small animals: Canine Arthritis, Small Animal Skin and Ears, Feline Urinary Problems, Small Animal Emergency Triage
- Equine: Equine Colic, Equine Lameness, Equine Respiratory Disease, Equine Wounds and First Aid
- Livestock: Large Animal Skin Infections, Livestock Foot Infections, Bovine Mastitis, Calf Diarrhoea, Sheep Parasites, Lambing and Calving Emergencies, Pig Respiratory Disease, Poultry Flock Health

Students collect a star for each category quiz when they score above 60%. After collecting all category stars, the quiz shows: "Congratulations, you could be a vet."

## Files

- `index.html` - the quiz app
- `assets/vet-mcq-banner.png` - banner image used by the quiz

## Run Locally

Open `index.html` in a browser, or serve the folder with:

```powershell
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Publish With GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, the `assets/` folder, this `README.md`, and `.gitignore`.
3. In GitHub, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/root` folder.
6. Save. GitHub will provide a public URL after the first deploy.

## Note

This quiz is for educational revision only and is not a substitute for current veterinary guidance or clinical judgement.
