# Changelog

## [0.5.0](https://github.com/zylon-ai/private-gpt/compare/v0.4.0...v0.5.0) (2024-04-02)


### Features

* **code:** improve concat of strings in ui ([#1785](https://github.com/zylon-ai/private-gpt/issues/1785)) ([bac818a](https://github.com/zylon-ai/private-gpt/commit/bac818add51b104cda925b8f1f7b51448e935ca1))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/zylon-ai/private-gpt/issues/1812)) ([f83abff](https://github.com/zylon-ai/private-gpt/commit/f83abff8bc955a6952c92cc7bcb8985fcec93afa))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/zylon-ai/private-gpt/issues/1782)) ([8a836e4](https://github.com/zylon-ai/private-gpt/commit/8a836e4651543f099c59e2bf497ab8c55a7cd2e5))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/zylon-ai/private-gpt/issues/1741)) ([5725181](https://github.com/zylon-ai/private-gpt/commit/572518143ac46532382db70bed6f73b5082302c1))
* **docs:** upgrade fern ([#1596](https://github.com/zylon-ai/private-gpt/issues/1596)) ([84ad16a](https://github.com/zylon-ai/private-gpt/commit/84ad16af80191597a953248ce66e963180e8ddec))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/zylon-ai/private-gpt/issues/1750)) ([134fc54](https://github.com/zylon-ai/private-gpt/commit/134fc54d7d636be91680dc531f5cbe2c5892ac56))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/zylon-ai/private-gpt/issues/1698)) ([1efac6a](https://github.com/zylon-ai/private-gpt/commit/1efac6a3fe19e4d62325e2c2915cd84ea277f04f))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/zylon-ai/private-gpt/issues/1703)) ([02dc83e](https://github.com/zylon-ai/private-gpt/commit/02dc83e8e9f7ada181ff813f25051bbdff7b7c6b))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/zylon-ai/private-gpt/issues/1800)) ([b3b0140](https://github.com/zylon-ai/private-gpt/commit/b3b0140e244e7a313bfaf4ef10eb0f7e4192710e))
* **llm:** Ollama timeout setting ([#1773](https://github.com/zylon-ai/private-gpt/issues/1773)) ([6f6c785](https://github.com/zylon-ai/private-gpt/commit/6f6c785dac2bbad37d0b67fda215784298514d39))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/zylon-ai/private-gpt/issues/1467)) ([821bca3](https://github.com/zylon-ai/private-gpt/commit/821bca32e9ee7c909fd6488445ff6a04463bf91b))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/zylon-ai/private-gpt/issues/1706)) ([68b3a34](https://github.com/zylon-ai/private-gpt/commit/68b3a34b032a08ca073a687d2058f926032495b3))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/zylon-ai/private-gpt/issues/1771)) ([087cb0b](https://github.com/zylon-ai/private-gpt/commit/087cb0b7b74c3eb80f4f60b47b3a021c81272ae1))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/zylon-ai/private-gpt/issues/1810)) ([83adc12](https://github.com/zylon-ai/private-gpt/commit/83adc12a8ef0fa0c13a0dec084fa596445fc9075))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/zylon-ai/private-gpt/issues/1783)) ([ea153fb](https://github.com/zylon-ai/private-gpt/commit/ea153fb92f1f61f64c0d04fff0048d4d00b6f8d0))
* **ui:** Add Model Information to ChatInterface label ([f0b174c](https://github.com/zylon-ai/private-gpt/commit/f0b174c097c2d5e52deae8ef88de30a0d9013a38))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/zylon-ai/private-gpt/issues/1705)) ([290b9fb](https://github.com/zylon-ai/private-gpt/commit/290b9fb084632216300e89bdadbfeb0380724b12))
* **UI:** Faster startup and document listing ([#1763](https://github.com/zylon-ai/private-gpt/issues/1763)) ([348df78](https://github.com/zylon-ai/private-gpt/commit/348df781b51606b2f9810bcd46f850e54192fd16))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/zylon-ai/private-gpt/issues/1643)) ([410bf7a](https://github.com/zylon-ai/private-gpt/commit/410bf7a71f17e77c4aec723ab80c233b53765964))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/zylon-ai/private-gpt/issues/1730)) ([63de7e4](https://github.com/zylon-ai/private-gpt/commit/63de7e4930ac90dd87620225112a22ffcbbb31ee))
* wipe per storage type ([#1772](https://github.com/zylon-ai/private-gpt/issues/1772)) ([c2d6948](https://github.com/zylon-ai/private-gpt/commit/c2d694852b4696834962a42fde047b728722ad74))


### Bug Fixes

* **docs:** Minor documentation amendment ([#1739](https://github.com/zylon-ai/private-gpt/issues/1739)) ([258d02d](https://github.com/zylon-ai/private-gpt/commit/258d02d87c5cb81d6c3a6f06aa69339b670dffa9))
* Fixed docker-compose ([#1758](https://github.com/zylon-ai/private-gpt/issues/1758)) ([774e256](https://github.com/zylon-ai/private-gpt/commit/774e2560520dc31146561d09a2eb464c68593871))
* **ingest:** update script label ([#1770](https://github.com/zylon-ai/private-gpt/issues/1770)) ([7d2de5c](https://github.com/zylon-ai/private-gpt/commit/7d2de5c96fd42e339b26269b3155791311ef1d08))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/zylon-ai/private-gpt/issues/1709)) ([d17c34e](https://github.com/zylon-ai/private-gpt/commit/d17c34e81a84518086b93605b15032e2482377f7))

## [0.4.0](https://github.com/imartinez/privateGPT/compare/v0.3.0...v0.4.0) (2024-03-06)


### Features

* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/imartinez/privateGPT/issues/1663)) ([45f0571](https://github.com/imartinez/privateGPT/commit/45f05711eb71ffccdedb26f37e680ced55795d44))
* **Vector:** support pgvector ([#1624](https://github.com/imartinez/privateGPT/issues/1624)) ([cd40e39](https://github.com/imartinez/privateGPT/commit/cd40e3982b780b548b9eea6438c759f1c22743a8))

## [0.3.0](https://github.com/imartinez/privateGPT/compare/v0.2.0...v0.3.0) (2024-02-16)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/imartinez/privateGPT/issues/1426)) ([e326126](https://github.com/imartinez/privateGPT/commit/e326126d0d4cd7e46a79f080c442c86f6dd4d24b))
* Add stream information to generate SDKs ([#1569](https://github.com/imartinez/privateGPT/issues/1569)) ([24fae66](https://github.com/imartinez/privateGPT/commit/24fae660e6913aac6b52745fb2c2fe128ba2eb79))
* **API:** Ingest plain text ([#1417](https://github.com/imartinez/privateGPT/issues/1417)) ([6eeb95e](https://github.com/imartinez/privateGPT/commit/6eeb95ec7f17a618aaa47f5034ee5bccae02b667))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/imartinez/privateGPT/issues/1432)) ([b178b51](https://github.com/imartinez/privateGPT/commit/b178b514519550e355baf0f4f3f6beb73dca7df2))
* **llm:** Add openailike llm mode ([#1447](https://github.com/imartinez/privateGPT/issues/1447)) ([2d27a9f](https://github.com/imartinez/privateGPT/commit/2d27a9f956d672cb1fe715cf0acdd35c37f378a5)), closes [#1424](https://github.com/imartinez/privateGPT/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/imartinez/privateGPT/issues/1526)) ([6bbec79](https://github.com/imartinez/privateGPT/commit/6bbec79583b7f28d9bea4b39c099ebef149db843))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/imartinez/privateGPT/issues/1437)) ([4780540](https://github.com/imartinez/privateGPT/commit/47805408703c23f0fd5cab52338142c1886b450b))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/imartinez/privateGPT/issues/1415)) ([8ec7cf4](https://github.com/imartinez/privateGPT/commit/8ec7cf49f40701a4f2156c48eb2fad9fe6220629))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/imartinez/privateGPT/issues/1397)) ([c71ae7c](https://github.com/imartinez/privateGPT/commit/c71ae7cee92463bbc5ea9c434eab9f99166e1363))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/imartinez/privateGPT/issues/1612)) ([aa13afd](https://github.com/imartinez/privateGPT/commit/aa13afde07122f2ddda3942f630e5cadc7e4e1ee))


### Bug Fixes

* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/imartinez/privateGPT/issues/1519)) ([869233f](https://github.com/imartinez/privateGPT/commit/869233f0e4f03dc23e5fae43cf7cb55350afdee9))
* **deploy:** fix local and external dockerfiles ([fde2b94](https://github.com/imartinez/privateGPT/commit/fde2b942bc03688701ed563be6d7d597c75e4e4e))
* **docker:** docker broken copy ([#1419](https://github.com/imartinez/privateGPT/issues/1419)) ([059f358](https://github.com/imartinez/privateGPT/commit/059f35840adbc3fb93d847d6decf6da32d08670c))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([0a89d76](https://github.com/imartinez/privateGPT/commit/0a89d76cc5ed4371ffe8068858f23dfbb5e8cc37))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/imartinez/privateGPT/issues/1449)) ([6191bcd](https://github.com/imartinez/privateGPT/commit/6191bcdbd6e92b6f4d5995967dc196c9348c5954))
* **settings:** correct yaml multiline string ([#1403](https://github.com/imartinez/privateGPT/issues/1403)) ([2564f8d](https://github.com/imartinez/privateGPT/commit/2564f8d2bb8c4332a6a0ab6d722a2ac15006b85f))
* **tests:** load the test settings only when running tests ([d3acd85](https://github.com/imartinez/privateGPT/commit/d3acd85fe34030f8cfd7daf50b30c534087bdf2b))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([24fb80c](https://github.com/imartinez/privateGPT/commit/24fb80ca38f21910fe4fd81505d14960e9ed4faa))

## [0.2.0](https://github.com/imartinez/privateGPT/compare/v0.1.0...v0.2.0) (2023-12-10)


### Features

* **llm:** drop default_system_prompt ([#1385](https://github.com/imartinez/privateGPT/issues/1385)) ([a3ed14c](https://github.com/imartinez/privateGPT/commit/a3ed14c58f77351dbd5f8f2d7868d1642a44f017))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/imartinez/privateGPT/issues/1353)) ([145f3ec](https://github.com/imartinez/privateGPT/commit/145f3ec9f41c4def5abf4065a06fb0786e2d992a))

## [0.1.0](https://github.com/imartinez/privateGPT/compare/v0.0.2...v0.1.0) (2023-11-30)


### Features

* Disable Gradio Analytics ([#1165](https://github.com/imartinez/privateGPT/issues/1165)) ([6583dc8](https://github.com/imartinez/privateGPT/commit/6583dc84c082773443fc3973b1cdf8095fa3fec3))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/imartinez/privateGPT/issues/1133)) ([64c5ae2](https://github.com/imartinez/privateGPT/commit/64c5ae214a9520151c9c2d52ece535867d799367))
* enable resume download for hf_hub_download ([#1249](https://github.com/imartinez/privateGPT/issues/1249)) ([4197ada](https://github.com/imartinez/privateGPT/commit/4197ada6267c822f32c1d7ba2be6e7ce145a3404))
* move torch and transformers to local group ([#1172](https://github.com/imartinez/privateGPT/issues/1172)) ([0d677e1](https://github.com/imartinez/privateGPT/commit/0d677e10b970aec222ec04837d0f08f1631b6d4a))
* Qdrant support ([#1228](https://github.com/imartinez/privateGPT/issues/1228)) ([03d1ae6](https://github.com/imartinez/privateGPT/commit/03d1ae6d70dffdd2411f0d4e92f65080fff5a6e2))


### Bug Fixes

* Docker and sagemaker setup ([#1118](https://github.com/imartinez/privateGPT/issues/1118)) ([895588b](https://github.com/imartinez/privateGPT/commit/895588b82a06c2bc71a9e22fb840c7f6442a3b5b))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/imartinez/privateGPT/issues/1123)) ([24cfddd](https://github.com/imartinez/privateGPT/commit/24cfddd60f74aadd2dade4c63f6012a2489938a1))
* Remove global state ([#1216](https://github.com/imartinez/privateGPT/issues/1216)) ([022bd71](https://github.com/imartinez/privateGPT/commit/022bd718e3dfc197027b1e24fb97e5525b186db4))
* sagemaker config and chat methods ([#1142](https://github.com/imartinez/privateGPT/issues/1142)) ([a517a58](https://github.com/imartinez/privateGPT/commit/a517a588c4927aa5c5c2a93e4f82a58f0599d251))
* typo in README.md ([#1091](https://github.com/imartinez/privateGPT/issues/1091)) ([ba23443](https://github.com/imartinez/privateGPT/commit/ba23443a70d323cd4f9a242b33fd9dce1bacd2db))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/imartinez/privateGPT/issues/1260)) ([0d52002](https://github.com/imartinez/privateGPT/commit/0d520026a3d5b08a9b8487be992d3095b21e710c))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/imartinez/privateGPT/issues/1280)) ([f1cbff0](https://github.com/imartinez/privateGPT/commit/f1cbff0fb7059432d9e71473cbdd039032dab60d))

## [0.0.2](https://github.com/imartinez/privateGPT/compare/v0.0.1...v0.0.2) (2023-10-20)


### Bug Fixes

* chromadb max batch size ([#1087](https://github.com/imartinez/privateGPT/issues/1087)) ([f5a9bf4](https://github.com/imartinez/privateGPT/commit/f5a9bf4e374b2d4c76438cf8a97cccf222ec8e6f))

## 0.0.1 (2023-10-20)

### Miscellaneous Chores

* Initial version ([490d93f](https://github.com/imartinez/privateGPT/commit/490d93fdc1977443c92f6c42e57a1c585aa59430))
