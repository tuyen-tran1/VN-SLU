# VN-SLU: A Vietnamese Spoken Language Understanding Dataset

Contact email: tuyencbt@gmail.com

This repository contains links to download the VN-SLU dataset and a brief overview of the dataset.

**Getting the data** 

Textual annotations and the corresponding acoustic data can be download from https://drive.google.com/drive/folders/1QJFQjwNl4tmlf4R1yt4W3gfUzsiF-kWp 

**Brief overview** 

Each VN-SLU entry has the following structure. It contains NLU annotations and information allowing to link with audio files, as well as the corresponding metadata information.

```json
{"id": "6483425ed9f5698f39420182",
"sentence": "trời tối quá, em mở giúp anh cái rèm cửa ra với",
"intent": "mở thiết bị",
"sentence_annotation": "trời tối quá, em mở giúp anh cái [ device : rèm ] cửa ra với",
"entities": [{"type": "device", "filler": "rèm"}],
"file": "6483425ed9f5698f39420182.wav"}