# Shulker View (Fabric 1.21.11)

Garde le tooltip vanilla des shulker boxes (liste des items + "et X de plus")
et ajoute en dessous une image de l'intérieur : grille 9x3 teintée de la couleur
de la shulker, avec les items, leurs quantités et leur durabilité.

## Build
1. Java 21 + IntelliJ IDEA (ou `gradle wrapper` puis `./gradlew build`)
2. Le jar est dans `build/libs/shulkerview-1.0.0.jar`
3. Mettre le jar + Fabric API dans `.minecraft/mods`

## Build sur GitHub
Le workflow `.github/workflows/build.yml` compile à chaque push.
- Jar : onglet **Actions** → dernier run → **Artifacts** → `shulkerview-jar`
- Release auto : `git tag v1.0.0 && git push --tags`
