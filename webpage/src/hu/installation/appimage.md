# Telepítés AppImage néven

You can download the latest AppImage from the [QOwnNotes releases page](https://github.com/pbek/QOwnNotes/releases). Meg kell nevezni a következő néven: `QOwnNotes-x86_64.AppImage`.

::: tip
Ha telepítve van a [jq](https://stedolan.github.io/jq/), közvetlenül letöltheti a legújabb AppImage-et is:

```bash
# query the latest Linux release from the QOwnNotes API, parse the JSON for the URL and download it
curl -L https://api.qownnotes.org/latest_releases/linux | jq .url | xargs curl -Lo QOwnNotes-x86_64.AppImage
```
:::

Ezután megváltoztathatja a fájl végrehajtási engedélyeit:

```bash
chmod a+x QOwnNotes-*.AppImage
```

Ezután képesnek kell lennie az AppImage futtatására a QOwnNotes futtatásához.

::: warning
Ha az **automatikus frissítőt** szeretné használni, feltétlenül helyezze el az AppImage -ot olyan helyre, ahová felhasználói fiókja írási jogosultsággal rendelkezik, például valahol a saját könyvtárában.
:::

::: tip
Ha problémái vannak az AppImage futtatásával, mert a glibc verziója túl régi, próbálkozzon az [OBS-re épített AppImage](https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/AppImage/QOwnNotes-latest-x86_64.AppImage) programmal, amelyet a glibc 2.16-os verziójával kell elkészíteni.
:::
