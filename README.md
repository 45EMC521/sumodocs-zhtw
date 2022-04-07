# SUMO 說明文件

SUMO 說明文件是以 [MkDocs](https://www.mkdocs.org/) 撰成。本 repository（SUMO 說明文件正體中文版）是非官方維護版本。

你可以在以下網址查看 SUMO 說明文件的中文版本：<https://sumodocs-zhtw.emc521.tw>。

或者，你也可以瀏覽本文件的原文（英文）版本：<https://sumo.dlr.de/docs/>。

## 入門

### 前置需求

- Python > 3.5 （*mkdocs-macros-plugin* 需要）

### 安裝到電腦上

Clone 這個 repository：

```
git clone https://github.com/eclipse/sumo.git
```

然後切換到 `sumodocs-zhtw`目錄內。

安裝 MkDocs、MkDocs 的外掛和 plantuml：

```
pip install -r requirements.txt
```

On Linux, install **plantuml** via `sudo apt-get install plantuml`.

To run the built-in development server, use:

```
mkdocs serve
```

`mkdocs serve` re-builds the entire site everytime it detects a change. If you want to only re-build the pages that have been modified, use `mkdocs serve --dirtyreload` ([read more](https://www.mkdocs.org/about/release-notes/#support-for-dirty-builds-990))

**To preview edition you should run the built-in development server and access the Documentation from the localhost address (which by default is 127.0.0.1:8000).**

To generate the final static html files, run:

```
mkdocs build
```

This should create the *site* directory, containing all the necessary HTML and CSS files.

## Contributing

Feel free to contribute and improve the SUMO Documentation. All changes need to be via Pull requests.
You can click on the "Edit on GitHub" button in the top right corner of every page, or just simply press the `e` key on your keyboard.

We encourage you to read [this guide](https://sumo.dlr.de/docs/Editing_Articles.html) on how to edit the articles.

You can also report typos and such, opening an issue [here](https://github.com/eclipse/sumo/issues).