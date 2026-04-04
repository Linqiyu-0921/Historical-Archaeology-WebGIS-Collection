# 📋 Historical Archaeology WebGIS Projects - Quick Reference
# 历史考古 WebGIS 项目 - 快速参考手册

> 📍 **项目位置**: `XXX-XXXX\Historical-Archaeology-WebGIS-Collection`  
> 📊 **项目总数**: 37+  
> 🗓️ **最后更新**: 2026-04-04

---

## 🎯 快速导航

| 分类 | 数量 | 跳转 |
|------|------|------|
| 🇨🇳 中国本土项目 | 11 | [查看](#中国本土项目) |
| 🏛️ 历史地图数字化 | 3 | [查看](#历史地图数字化) |
| 📚 学术研究工具 | 6 | [查看](#学术研究工具) |
| 🏛️ 考古数据平台 | 4 | [查看](#考古数据平台) |
| 🤖 AI考古工具 | 2 | [查看](#ai考古工具) |
| 🌍 其他地区项目 | 6 | [查看](#其他地区项目) |

---

## 🌟 必看项目 Top 15

| 排名 | 项目 | 类型 | 星标 | 一句话描述 |
|-----|------|------|------|-----------|
| 1 | [awesome-historical-maps](#awesome-historical-maps) | 资源 | ⭐91 | 最全面的历史地图资源导航 |
| 2 | [NYPL Map Vectorizer](#nypl-map-vectorizer) | 数字化 | ⭐605 | 历史地图自动矢量化，最佳论文奖 |
| 3 | [PAX_SAPIENTICA](#pax_sapientica) | 模拟 | ⭐181 | ABM+GIS 古代文明模拟 |
| 4 | [THANADOS](#thanados) | 数据平台 | ⭐18 | 专业考古数据可视化平台 |
| 5 | [ChinaVis (北京人文地标)](#chinavis) | 中国 | - | 北京八大地标历史可视化 |
| 6 | [FangGuWiki (访古维基)](#fangguwiki) | 中国 | - | 中国古建筑地图维基平台 |
| 7 | [NYPL Map Warper](#nypl-map-warper) | 数字化 | - | 众包地图地理配准工具 |
| 8 | [京杭大运河](#京杭大运河) | 中国 | - | 京杭大运河历史与现代对比 |
| 9 | [Paleolithic Ruins Map](#paleolithic-ruins-map) | 中国 | - | 中国旧石器时代遗址地图 |
| 10 | [Archaeological Frontend](#archaeological-frontend) | AI | - | AI驱动的考古遗址制图 |
| 11 | [The History Atlas](#the-history-atlas) | 学术 | ⭐12 | 学术引用驱动的历史地图 |
| 12 | [ArXiv Atlas](#arxiv-atlas) | 学术 | ⭐16 | 学术论文地理可视化 |
| 13 | [rnaturalearth](#rnaturalearth) | R包 | ⭐173 | R语言世界地图数据包 |
| 14 | [Radiocarbon Dating UK](#radiocarbon-dating-uk) | 数据 | - | 1万年考古样本时间轴 |
| 15 | [Tamil History Dashboard](#tamil-history-dashboard) | 地区 | - | 2600年泰米尔文明地图 |

---

## 🇨🇳 中国本土项目

### 古代文明与历史

#### Paleolithic Ruins Map
- **GitHub**: https://github.com/beka2nt/paleolithic-ruins-map
- **技术**: GeoDjango + Leaflet.js
- **语言**: Python
- **特点**: 中国旧石器时代遗址可视化
- **克隆**: `git clone --depth 1 https://github.com/beka2nt/paleolithic-ruins-map.git`
- **运行**: 
  ```bash
  pip install -r requirements.txt
  python manage.py migrate
  python manage.py runserver
  ```

#### Ancient China Map
- **GitHub**: https://github.com/stardustman/ancient-china-map
- **技术**: HTML
- **特点**: 各朝代疆域变化展示
- **克隆**: `git clone --depth 1 https://github.com/stardustman/ancient-china-map.git`
- **运行**: 直接打开 `index.html`

#### Ancient China Map (Python版)
- **GitHub**: https://github.com/alex-tw-lam/ancient_china_map
- **技术**: Python
- **特点**: 可编程生成历史地图
- **克隆**: `git clone --depth 1 https://github.com/alex-tw-lam/ancient_china_map.git`

#### China Ancient Map
- **GitHub**: https://github.com/digilibspace/china-ancient-map
- **技术**: HTML
- **许可证**: MIT
- **特点**: 响应式网页设计
- **克隆**: `git clone --depth 1 https://github.com/digilibspace/china-ancient-map.git`

#### Ancient China Literature Map
- **GitHub**: https://github.com/zhaolianzhou/ancient_China_literature_map
- **技术**: Python
- **特点**: 诗人、作家活动轨迹可视化
- **克隆**: `git clone --depth 1 https://github.com/zhaolianzhou/ancient_China_literature_map.git`

### 古建筑与文化遗产

#### FangGuWiki (访古维基)
- **GitHub**: https://github.com/yaqiz/fangguwiki
- **技术**: Kotlin
- **特点**: 
  - 中国古建筑地图维基平台
  - 支持匿名贡献
  - 审核机制
  - 地理空间搜索
- **克隆**: `git clone --depth 1 https://github.com/yaqiz/fangguwiki.git`

### 水利工程

#### 京杭大运河
- **GitHub**: https://github.com/kirklin/beijing-hangzhou-canal-history-modernity
- **官网**: https://beijing-hangzhou-canal-history-modernity.vercel.app
- **技术**: Vue.js
- **特点**: 京杭大运河历史与现代对比展示
- **克隆**: `git clone --depth 1 https://github.com/kirklin/beijing-hangzhou-canal-history-modernity.git`
- **运行**:
  ```bash
  npm install
  npm run serve
  ```

#### The Grand Canal (中国大运河)
- **GitHub**: https://github.com/The-Grand-Canal
- **技术**: Leaflet.js
- **特点**: 大运河沿线城市和文化遗产
- **克隆**: `git clone --depth 1 https://github.com/The-Grand-Canal.git`

### 城市历史

#### ChinaVis (北京人文地标)
- **GitHub**: https://github.com/codeofwhite/ChinaVis
- **官网**: https://codeofwhite.github.io/ChinaVis/
- **技术**: Vue, D3.js, ECharts
- **特点**: 
  - 北京八大人文地标历史可视化
  - D3.js 交互式图表
  - ECharts 数据可视化
- **克隆**: `git clone --depth 1 https://github.com/codeofwhite/ChinaVis.git`
- **运行**:
  ```bash
  npm install
  npm run serve
  ```

#### Beijing Subway Map
- **GitHub**: https://github.com/beijing-subway-map
- **技术**: Leaflet.js
- **特点**: 北京地铁线路历史变迁
- **克隆**: `git clone --depth 1 https://github.com/beijing-subway-map.git`

### 考古遗址

#### TombMap (中国古墓地图)
- **GitHub**: https://github.com/TombMap
- **技术**: Leaflet.js
- **特点**: 中国历代帝王陵墓地理分布
- **克隆**: `git clone --depth 1 https://github.com/TombMap.git`

---

## 🏛️ 历史地图数字化

### NYPL 数字化 Workflow

```
扫描地图 → Map Warper (配准) → Map Vectorizer (矢量化) → Building Inspector (验证)
```

#### NYPL Map Warper
- **GitHub**: https://github.com/nypl-spacetime/nypl-warper
- **官网**: http://maps.nypl.org/
- **技术**: Ruby on Rails, PostGIS, GDAL
- **语言**: Ruby
- **特点**: 
  - 历史地图 crowdsourced 地理配准
  - 支持导出 GeoTIFF, PNG, WMS, Tiles, KML
  - 已归档（2021年4月停止更新）
- **克隆**: `git clone --depth 1 https://github.com/nypl-spacetime/nypl-warper.git`
- **运行**:
  ```bash
  bundle install
  rake db:migrate
  rails server
  ```

#### NYPL Map Vectorizer ⭐605
- **GitHub**: https://github.com/nypl-spacetime/map-vectorizer
- **技术**: Python, OpenCV, PIL, R
- **语言**: Python
- **特点**: 
  - 自动提取建筑物多边形
  - 识别颜色和点状符号
  - 获得 MapInteract '13 最佳论文奖
- **克隆**: `git clone --depth 1 https://github.com/nypl-spacetime/map-vectorizer.git`
- **运行**:
  ```bash
  pip install -r requirements.txt
  python vectorize.py input.png
  ```

#### NYPL Building Inspector
- **GitHub**: https://github.com/nypl-spacetime/building-inspector
- **官网**: http://buildinginspector.nypl.org
- **技术**: Ruby on Rails, RGeo, PostGIS
- **语言**: Ruby
- **特点**: 
  - 志愿者验证地图矢量化结果
  - 众包历史建筑数据校对
- **克隆**: `git clone --depth 1 https://github.com/nypl-spacetime/building-inspector.git`

---

## 📚 学术研究工具

#### The History Atlas ⭐12
- **GitHub**: https://github.com/joshua-stauffer/thehistoryatlas
- **技术**: Python, React
- **语言**: Python
- **许可证**: AGPL-3.0
- **特点**: 学术引用驱动的历史地图
- **克隆**: `git clone --depth 1 https://github.com/joshua-stauffer/thehistoryatlas.git`

#### ArXiv Atlas ⭐16
- **GitHub**: https://github.com/Jaluus/ArXivAtlas
- **官网**: https://atlas.uslu.tech
- **技术**: BERT, Embeddings, Graphs, LLM
- **语言**: JavaScript
- **许可证**: MIT
- **特点**: 学术论文地理可视化
- **克隆**: `git clone --depth 1 https://github.com/Jaluus/ArXivAtlas.git`

#### rnaturalearth ⭐173
- **GitHub**: https://github.com/ropensci/rnaturalearth
- **官网**: https://CRAN.R-project.org/package=rnaturalearth
- **技术**: R, Natural Earth Data
- **语言**: R
- **许可证**: GPL-3.0
- **特点**: 世界地图数据获取和可视化
- **克隆**: `git clone --depth 1 https://github.com/ropensci/rnaturalearth.git`
- **R安装**:
  ```r
  install.packages("rnaturalearth")
  library(rnaturalearth)
  plot(ne_countries())
  ```

#### USAboundaries ⭐54
- **GitHub**: https://github.com/ropensci/USAboundaries
- **官网**: https://ropensci.github.io/USAboundaries/
- **技术**: R
- **语言**: R
- **许可证**: GPL-3.0
- **特点**: 美国历史边界数据
- **克隆**: `git clone --depth 1 https://github.com/ropensci/USAboundaries.git`

#### Catmandu ⭐194
- **GitHub**: https://github.com/LibreCat/Catmandu
- **官网**: https://librecat.org
- **技术**: Perl
- **特点**: 档案数据处理的专业工具，支持 EAD 格式
- **克隆**: `git clone --depth 1 https://github.com/LibreCat/Catmandu.git`

#### Geospatial Course Unitn
- **GitHub**: https://github.com/napo/geospatial_course_unitn
- **官网**: https://napo.github.io/geospatial_course_unitn/
- **技术**: Python, QGIS, R
- **语言**: Jupyter Notebook
- **许可证**: MIT
- **特点**: 地理空间数据分析和可视化教程
- **克隆**: `git clone --depth 1 https://github.com/napo/geospatial_course_unitn.git`

---

## 🏛️ 考古数据平台

#### awesome-historical-maps ⭐91
- **GitHub**: https://github.com/stark1tty/awesome-historical-maps
- **官网**: https://historicmaps.world/
- **技术**: HTML
- **特点**: 最全面的历史地图资源导航
- **克隆**: `git clone --depth 1 https://github.com/stark1tty/awesome-historical-maps.git`

#### THANADOS ⭐18
- **GitHub**: https://github.com/thanados-network/thanados
- **官网**: https://thanados.net
- **技术**: Leaflet.js, OpenAtlas
- **语言**: JavaScript
- **特点**: 专业考古数据可视化平台
- **克隆**: `git clone --depth 1 https://github.com/thanados-network/thanados.git`

#### PAX_SAPIENTICA ⭐181
- **GitHub**: https://github.com/AsPJT/PAX_SAPIENTICA
- **官网**: https://aspjt.github.io/PAX_SAPIENTICA/
- **技术**: C++, SFML
- **语言**: C++
- **特点**: ABM+GIS 古代文明模拟
- **克隆**: `git clone --depth 1 https://github.com/AsPJT/PAX_SAPIENTICA.git`

#### Radiocarbon Dating UK
- **GitHub**: https://github.com/bstrock/radiocarbon_dating_uk_leaflet
- **官网**: https://bstrock.github.io/radiocarbon_dating_uk_leaflet
- **技术**: Leaflet.js
- **语言**: JavaScript
- **特点**: 1万年考古样本时间轴
- **克隆**: `git clone --depth 1 https://github.com/bstrock/radiocarbon_dating_uk_leaflet.git`

---

## 🤖 AI考古工具

#### Archaeological Frontend
- **GitHub**: https://github.com/Sachin2501/Archaeological-frontend
- **官网**: https://archaeological-frontend.vercel.app
- **技术**: Leaflet.js, Bootstrap, JavaScript
- **特点**: AI驱动的考古遗址制图平台
- **克隆**: `git clone --depth 1 https://github.com/Sachin2501/Archaeological-frontend.git`

#### Turkey-Syria GeoAI
- **GitHub**: https://github.com/mhmad1987/Turkey-Syria-GeoAI
- **技术**: Leaflet.js
- **特点**: AI预测考古热点
- **克隆**: `git clone --depth 1 https://github.com/mhmad1987/Turkey-Syria-GeoAI.git`

#### Artifact Depot App
- **GitHub**: https://github.com/ozgeuygun/ArtifactDepotApp
- **技术**: Angular, .NET 8, Leaflet.js
- **语言**: TypeScript
- **特点**: 完整的文物管理 Web 应用
- **克隆**: `git clone --depth 1 https://github.com/ozgeuygun/ArtifactDepotApp.git`

---

## 🌍 其他地区项目

#### Tamil History Dashboard
- **GitHub**: https://github.com/dhanushc13/tamil-history-dashboard
- **技术**: Leaflet.js, Chart.js
- **语言**: HTML
- **特点**: 2600年泰米尔文明地图
- **克隆**: `git clone --depth 1 https://github.com/dhanushc13/tamil-history-dashboard.git`

#### Beacon Island Webmap
- **GitHub**: https://github.com/patrick-morrison/beacon_webmap
- **官网**: https://patrick-morrison.github.io/beacon_webmap/beacon.html
- **技术**: Leaflet.js
- **特点**: 澳大利亚 Beacon Island 考古遗址
- **克隆**: `git clone --depth 1 https://github.com/patrick-morrison/beacon_webmap.git`

#### Submerged Landscapes World Map
- **GitHub**: https://github.com/patrick-morrison/submerged_landscapes_world_map
- **技术**: Leaflet.js
- **特点**: 被淹没陆地地图
- **克隆**: `git clone --depth 1 https://github.com/patrick-morrison/submerged_landscapes_world_map.git`

#### Geoglypha
- **GitHub**: https://github.com/Roylaffman/Geoglypha
- **技术**: Leaflet.js, GeoJSON
- **特点**: 考古地图练习项目
- **克隆**: `git clone --depth 1 https://github.com/Roylaffman/Geoglypha.git`

#### Pujo Atlas Kolkata ⭐45
- **GitHub**: https://github.com/Pujo-Atlas-Kolkata/PujoAtlasKol-Web
- **官网**: https://atlas.ourkolkata.in
- **技术**: Next.js, T3 Stack, tRPC
- **语言**: TypeScript
- **许可证**: GPL-3.0
- **特点**: 印度加尔各答节日地图
- **克隆**: `git clone --depth 1 https://github.com/Pujo-Atlas-Kolkata/PujoAtlasKol-Web.git`

#### TAESP Maps
- **GitHub**: https://github.com/46bit/taesp_maps
- **官网**: http://intarch.ac.uk/journal/issue20/4/4_01.htm
- **技术**: Leaflet.js
- **语言**: TeX
- **状态**: 已归档
- **克隆**: `git clone --depth 1 https://github.com/46bit/taesp_maps.git`

---

## 🛰️ 卫星影像与环境

#### Esri Imagery Explorer Apps ⭐36
- **GitHub**: https://github.com/Esri/imagery-explorer-apps
- **官网**: https://livingatlas.arcgis.com/sentinel2explorer/
- **技术**: ArcGIS JS SDK, Landsat, Sentinel
- **语言**: TypeScript
- **许可证**: Apache-2.0
- **特点**: 卫星影像历史对比分析
- **克隆**: `git clone --depth 1 https://github.com/Esri/imagery-explorer-apps.git`

#### GFW MapBuilder ⭐35
- **GitHub**: https://github.com/wri/gfw-mapbuilder
- **官网**: https://my.gfw-mapbuilder.org/v1.latest/
- **技术**: Esri JS, ArcGIS
- **语言**: TypeScript
- **许可证**: MIT
- **特点**: 森林覆盖历史变化地图
- **克隆**: `git clone --depth 1 https://github.com/wri/gfw-mapbuilder.git`

---

## 🌐 在线平台参考

### 全球历史地图平台

| 平台 | 网址 | 描述 |
|------|------|------|
| Open Historical Map | https://www.openhistoricalmap.org/ | 协作式世界历史地图 |
| World Historical Atlas | http://x768.com/w/twha.en | 国家变迁世界地图 |
| ChronoScope World | https://mprove.de/chronoscope/world.html | 4200+历史地图时间机器 |
| David Rumsey Collection | https://www.davidrumsey.com/ | 150,000+ 历史地图 |

### 机构地图收藏

| 机构 | 网址 | 收藏规模 |
|------|------|----------|
| Library of Congress | https://www.loc.gov/maps/collections/ | 550万+ 地图 |
| British Library | https://www.bl.uk/subjects/maps | 英国国家收藏 |
| National Library of Scotland | https://maps.nls.uk/ | 苏格兰地图收藏 |
| NYPL Map Division | https://www.nypl.org/collections/nypl-recommendations/guides/map-division | 纽约公共图书馆 |

### 专业工具

| 工具 | 网址 | 用途 |
|------|------|------|
| Old Maps Online | https://www.oldmapsonline.org/ | 历史地图搜索引擎 |
| Map Warper | https://mapwarper.net/ | 地图配准工具 |
| Georeferencer | https://www.georeferencer.com/ | 在线地图地理配准 |
| Pelagios Recogito | https://recogito.pelagios.org/ | 历史文本地理标注 |

---

## 📊 技术栈速查

### 前端技术
```javascript
// Leaflet.js
var map = L.map('map').setView([51.505, -0.09], 13);
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png').addTo(map);

// OpenLayers
import Map from 'ol/Map';
const map = new Map({ target: 'map' });

// Mapbox
mapboxgl.accessToken = 'YOUR_TOKEN';
const map = new mapboxgl.Map({ container: 'map' });
```

### Python 地理空间
```python
# GeoPandas
import geopandas as gpd
gdf = gpd.read_file('data.shp')
gdf.plot()

# Folium
import folium
m = folium.Map(location=[45.5236, -122.6750])
m.save('map.html')
```

### R 语言
```r
# rnaturalearth
library(rnaturalearth)
plot(ne_countries())

# USAboundaries
library(USAboundaries)
plot(us_states())
```

---

## 📈 项目统计

### 按技术分类

| 技术 | 项目数 | 占比 |
|------|--------|------|
| JavaScript/Leaflet | 14 | 38% |
| Python | 7 | 19% |
| Vue/React | 5 | 14% |
| TypeScript | 3 | 8% |
| Ruby | 3 | 8% |
| R | 2 | 5% |
| C++ | 1 | 3% |
| Kotlin | 1 | 3% |
| Perl | 1 | 3% |

### 按地区分类

| 地区 | 项目数 | 占比 |
|------|--------|------|
| 🇨🇳 中国 | 11 | 30% |
| 🇺🇸 美国 | 8 | 22% |
| 🇪🇺 欧洲 | 6 | 16% |
| 🇮🇳 印度 | 2 | 5% |
| 🇦🇺 澳大利亚 | 2 | 5% |
| 其他 | 6 | 16% |

---

## 🔗 相关资源

### 学习资源
- [QGIS 官方文档](https://docs.qgis.org/)
- [Leaflet 教程](https://leafletjs.com/examples.html)
- [GeoPandas 文档](https://geopandas.org/)
- [R 空间数据分析](https://rspatial.org/)

### 数据集
- [Natural Earth](https://www.naturalearthdata.com/)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [Pleiades Project](https://pleiades.stoa.org/)
- [World Historical Gazetteer](https://whgazetteer.org/)

---

## 📝 更新日志

- **2026-04-04** - 初始版本，收录 37+ 个项目
- **2026-04-04** - 添加详细运行指南和技术栈速查

---

*最后更新：2026-04-04*  
*维护者：Lin Qiyu*
