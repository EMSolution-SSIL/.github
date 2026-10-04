# EMSolution-SSIL

**電磁界解析・電動機設計のためのシミュレーションソフトウェアとオープンなエンジニアリングツール**

株式会社サイエンスソリューションズ（Science Solutions International Laboratory, Inc.; SSIL）は、電磁界解析、電動機設計、最適化、マルチフィジックスCAEのためのシミュレーションソフトウェアを開発しています。

このGitHub Organizationでは、当社のシミュレーションおよびエンジニアリング環境を支えるオープンソース／Source-Availableのツール、ユーティリティ、サンプル、ドキュメントを公開しています。

## 製品・エンジニアリングエコシステム

SSILでは、電磁界解析、電動機設計、最適化、マルチフィジックスCAEのためのシミュレーションソフトウェアおよびエンジニアリングツールを開発しています。

### [EMSolution : pyemsol（Python bind）](https://emsolution-ssil.github.io/EMSolutionDocs/index.html)

<img width="232" height="54.5" alt="EM_logo_201110_w" src="https://github.com/user-attachments/assets/72b82835-9e91-40d9-94bc-01f3853faf3b" />

有限要素法を用いた電磁界解析ソフトウェアです。`pyemsol` は、Python APIからEMSolutionを利用するためのPython bind版です。

### [eMotorSolution](https://emsolution-ssil.github.io/eMotorSolutionDoc/)

<img width="191.625" height="58.125" alt="eMotorSolution_logo1" src="https://github.com/user-attachments/assets/8ace8863-e9b4-41ae-866e-48fb7536c46b" />

電磁界解析をベースとした電動機の設計・解析ソフトウェアです。

### [EMSOptimizer](https://emsolution-ssil.github.io/EMSOptimizerDoc/)

<img width="261.3" height="52.3" alt="EMSOptimizer_logo1" src="https://github.com/user-attachments/assets/39565e01-e7a9-4b44-a877-527c32261300" />

CAEを活用した設計ワークフローのための最適化ソフトウェアです。

### [eMachineSim](https://emsolution-ssil.github.io/eMachineSimDocs/)

<img width="264.78" height="49.565" alt="emachinesim-logo" src="https://github.com/user-attachments/assets/107387f9-264d-4ddc-907a-579e558f98a3" />

熱解析・構造解析などを含む、電動機向けマルチフィジックスシミュレーションソフトウェアです。

このGitHub Organizationでは、これらのエンジニアリングワークフローに関連するオープンソースツール、ユーティリティ、サンプル、ドキュメントを公開しています。

## オープンソース／Source-Availableプロジェクト

CAEおよびエンジニアリングワークフローのためのオープンソース／Source-Availableツールを開発・公開しています。

### メッシュ・CAEユーティリティ

- [ems_mesh_checker](https://github.com/EMSolution-SSIL/ems_mesh_checker)  
  有限要素モデルのメッシュトポロジーおよびProperty境界を抽出するツールです。形状の再構築と、DXF、Gmsh GEO、Femap Neutral形式への出力に対応しています。

- [ems_mesh_morpher](https://github.com/EMSolution-SSIL/ems_mesh_morpher)  
  有限要素解析およびEMSolutionワークフロー向けのメッシュモーフィングツールです。規定変位、IDW、RBF、Weighted Laplaceによる変位伝播、導体表面のskin-layer生成、pyemsol DEFORM連成などに対応しています。

- [ems_file_format_converter](https://github.com/EMSolution-SSIL/ems_file_format_converter)  
  CAEメッシュおよび解析データのファイル形式変換ツールです。ATLAS、UNV、Femap NEU、Gmsh MSH形式などに対応しています。

- [airgap_force_fft](https://github.com/EMSolution-SSIL/airgap_force_fft)  
  モータのエアギャップ磁束密度結果を後処理するPythonツールです。Maxwell応力による電磁力・トルク評価、および2次元FFTを用いた時間・空間高調波解析に対応しています。

- [pyemsi](https://github.com/EMSolution-SSIL/pyemsi)  
  EMSolutionの解析データ変換、およびVTK／PyVistaを用いた対話的な3次元可視化のためのPythonツールです。

- [EMS_MaterialManager](https://github.com/EMSolution-SSIL/EMS_MaterialManager)  
  EMSolutionワークフロー向けの材料データ管理・交換ツールです。PolyForm Perimeter Licenseの下で公開しています。材料データの登録、検証、再利用、および標準化されたJSON形式によるエンジニアリングデータ交換に対応しています。

このほか、メッシュ処理やメッシュモーフィングに関するオープンなエンジニアリングツールを継続して開発しています。

## SSILについて

株式会社サイエンスソリューションズ（Science Solutions International Laboratory, Inc.）は、電磁界解析および電動機設計を中心に、エンジニアリングソフトウェアと数値シミュレーション技術を開発しています。

詳しくは以下をご覧ください。

[EMSolution / SSIL Webサイト](https://www.ssil.co.jp/product/EMSolution/en/)

> **注:** 現在、Webサイトを更新中です。

## English README

English version is available at [`README.md`](README.md).
