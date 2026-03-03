# MOV MetaEdit

___Embed and edit Universal Ad ID metadata in MOV or MP4 files___

MOV MetaEdit is a tool that supports the embedding and editing of metadata in MOV (Apple QuickTime) 
or MP4 (ISO/IEC 14496-14 a.k.a. MPEG-4 Part 14) files.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.MOVMetaEdit
flatpak run net.mediaarea.MOVMetaEdit
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.MOVMetaEdit.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.MOVMetaEdit.json
```
