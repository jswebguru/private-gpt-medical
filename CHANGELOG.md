# Changelog

## 0.0.1 (2024-10-04)


### Features

* add mistral + chatml prompts ([#1426](https://github.com/jswebguru/private-gpt-medical/issues/1426)) ([ae5dd60](https://github.com/jswebguru/private-gpt-medical/commit/ae5dd600370f3bb6b7ae3ce9a742bdecf0571f2b))
* Add stream information to generate SDKs ([#1569](https://github.com/jswebguru/private-gpt-medical/issues/1569)) ([f49be1a](https://github.com/jswebguru/private-gpt-medical/commit/f49be1afd6a5cc995ca8e4d2b3051a305731f45a))
* **API:** Ingest plain text ([#1417](https://github.com/jswebguru/private-gpt-medical/issues/1417)) ([f69a5a1](https://github.com/jswebguru/private-gpt-medical/commit/f69a5a1f53a240cd9836947d41cb8514e908e6c4))
* **bulk-ingest:** Add --ignored Flag to Exclude Specific Files and Directories During Ingestion ([#1432](https://github.com/jswebguru/private-gpt-medical/issues/1432)) ([e153c38](https://github.com/jswebguru/private-gpt-medical/commit/e153c388b2ead2199f2032c502c92897931fdcde))
* bump dependencies ([#1987](https://github.com/jswebguru/private-gpt-medical/issues/1987)) ([654fc03](https://github.com/jswebguru/private-gpt-medical/commit/654fc036f691f1e23944c1670ca37753dfd6b3e8))
* **code:** improve concat of strings in ui ([#1785](https://github.com/jswebguru/private-gpt-medical/issues/1785)) ([8a4cf3c](https://github.com/jswebguru/private-gpt-medical/commit/8a4cf3c110cd1e03251620ec1a4d495dd6522955))
* Disable Gradio Analytics ([#1165](https://github.com/jswebguru/private-gpt-medical/issues/1165)) ([a3ec531](https://github.com/jswebguru/private-gpt-medical/commit/a3ec531b3e6ed6ebd65ba2efdef6944503b22bdf))
* **docker:** set default Docker to use Ollama ([#1812](https://github.com/jswebguru/private-gpt-medical/issues/1812)) ([cb49fbd](https://github.com/jswebguru/private-gpt-medical/commit/cb49fbd619201e0e0cb191b92359f3c8da58c683))
* **docs:** Add guide Llama-CPP Linux AMD GPU support ([#1782](https://github.com/jswebguru/private-gpt-medical/issues/1782)) ([11a8f8a](https://github.com/jswebguru/private-gpt-medical/commit/11a8f8a51450287474c294bcbd45ce2c79fe5829))
* **docs:** add privategpt-ts sdk ([#1924](https://github.com/jswebguru/private-gpt-medical/issues/1924)) ([7e11e39](https://github.com/jswebguru/private-gpt-medical/commit/7e11e390b147b91086aebef158d28ba56a55b79c))
* **docs:** Feature/upgrade docs ([#1741](https://github.com/jswebguru/private-gpt-medical/issues/1741)) ([eae5b9c](https://github.com/jswebguru/private-gpt-medical/commit/eae5b9c6bff4a3e455cc2f0933186966e5f464be))
* **docs:** Fix setup docu ([#1926](https://github.com/jswebguru/private-gpt-medical/issues/1926)) ([50bb877](https://github.com/jswebguru/private-gpt-medical/commit/50bb87777ca5f31458152b9b33dc03809dc21433))
* **docs:** update doc for ipex-llm ([#1968](https://github.com/jswebguru/private-gpt-medical/issues/1968)) ([1ae49b9](https://github.com/jswebguru/private-gpt-medical/commit/1ae49b91b7e06be28ac39fa7e6d349aba9c06a8c))
* **docs:** upgrade fern ([#1596](https://github.com/jswebguru/private-gpt-medical/issues/1596)) ([fa13de2](https://github.com/jswebguru/private-gpt-medical/commit/fa13de207ed424f4e276b590abdcdcb497e11e15))
* Drop loguru and use builtin `logging` ([#1133](https://github.com/jswebguru/private-gpt-medical/issues/1133)) ([2573433](https://github.com/jswebguru/private-gpt-medical/commit/2573433b2ec79f8ab39ba0198797110bf536871c))
* enable resume download for hf_hub_download ([#1249](https://github.com/jswebguru/private-gpt-medical/issues/1249)) ([5e4eb45](https://github.com/jswebguru/private-gpt-medical/commit/5e4eb457a43b0e4f9bb969dd2df210590e4820d4))
* Get answers using preferred number of chunks ([7dd8ba8](https://github.com/jswebguru/private-gpt-medical/commit/7dd8ba8f3714f9cddebe8e3437aabfb46c85bd10))
* **ingest:** Created a faster ingestion mode - pipeline ([#1750](https://github.com/jswebguru/private-gpt-medical/issues/1750)) ([9566b13](https://github.com/jswebguru/private-gpt-medical/commit/9566b13b21539267d5144796d2a1f436ed105ee5))
* **llm - embed:** Add support for Azure OpenAI ([#1698](https://github.com/jswebguru/private-gpt-medical/issues/1698)) ([afafbcf](https://github.com/jswebguru/private-gpt-medical/commit/afafbcfe48bf454a87b4dc39a24a5938843ae4b6))
* **llm:** Add openailike llm mode ([#1447](https://github.com/jswebguru/private-gpt-medical/issues/1447)) ([49633a0](https://github.com/jswebguru/private-gpt-medical/commit/49633a039297fa7ff3519a907f077a7d7fd03d56)), closes [#1424](https://github.com/jswebguru/private-gpt-medical/issues/1424)
* **llm:** Add support for Ollama LLM ([#1526](https://github.com/jswebguru/private-gpt-medical/issues/1526)) ([c644fa4](https://github.com/jswebguru/private-gpt-medical/commit/c644fa4b62a2f0825e13194b286f762e23935120))
* **llm:** adds serveral settings for llamacpp and ollama ([#1703](https://github.com/jswebguru/private-gpt-medical/issues/1703)) ([03fdd0f](https://github.com/jswebguru/private-gpt-medical/commit/03fdd0f2ce14a2ab6002c5b73b3dc43bee978b4f))
* **llm:** drop default_system_prompt ([#1385](https://github.com/jswebguru/private-gpt-medical/issues/1385)) ([0b1923e](https://github.com/jswebguru/private-gpt-medical/commit/0b1923e3cc153f2b4e9cda438879c41411d4958c))
* **llm:** Ollama LLM-Embeddings decouple + longer keep_alive settings ([#1800](https://github.com/jswebguru/private-gpt-medical/issues/1800)) ([c884fe0](https://github.com/jswebguru/private-gpt-medical/commit/c884fe0b4d1e0907627c58a3d3e1db2adf746213))
* **llm:** Ollama timeout setting ([#1773](https://github.com/jswebguru/private-gpt-medical/issues/1773)) ([329ede8](https://github.com/jswebguru/private-gpt-medical/commit/329ede8f915b94a29f1f2e7c5f26b74279bc9863))
* **llm:** Support for Google Gemini LLMs and Embeddings ([#1965](https://github.com/jswebguru/private-gpt-medical/issues/1965)) ([a945014](https://github.com/jswebguru/private-gpt-medical/commit/a9450141e83ae79a804b8ee8c8fd7b8d010e49e3))
* **local:** tiktoken cache within repo for offline ([#1467](https://github.com/jswebguru/private-gpt-medical/issues/1467)) ([ce30522](https://github.com/jswebguru/private-gpt-medical/commit/ce305222004abf62c5152519e6831416a520d56a))
* move torch and transformers to local group ([#1172](https://github.com/jswebguru/private-gpt-medical/issues/1172)) ([f1319f5](https://github.com/jswebguru/private-gpt-medical/commit/f1319f539785171546e90011790fb4bcbc0ec243))
* **nodestore:** add Postgres for the doc and index store ([#1706](https://github.com/jswebguru/private-gpt-medical/issues/1706)) ([9753ed5](https://github.com/jswebguru/private-gpt-medical/commit/9753ed5f6e75440c757c4b25c4308721f8ae8714))
* prompt_style applied to all LLMs + extra LLM params. ([#1835](https://github.com/jswebguru/private-gpt-medical/issues/1835)) ([90b0d84](https://github.com/jswebguru/private-gpt-medical/commit/90b0d8454e2a615730dfde37065c3bc53c2f4d0c))
* Qdrant support ([#1228](https://github.com/jswebguru/private-gpt-medical/issues/1228)) ([1045f28](https://github.com/jswebguru/private-gpt-medical/commit/1045f28473f5e67c8e9eb1d52796e0d3a75c4241))
* **rag:** expose similarity_top_k and similarity_score to settings ([#1771](https://github.com/jswebguru/private-gpt-medical/issues/1771)) ([9aa2f37](https://github.com/jswebguru/private-gpt-medical/commit/9aa2f37c12bd7778e1b5ebbd104080d57baa5cd7))
* **RAG:** Introduce SentenceTransformer Reranker ([#1810](https://github.com/jswebguru/private-gpt-medical/issues/1810)) ([15dd6d9](https://github.com/jswebguru/private-gpt-medical/commit/15dd6d9f7d4985a8ca9f1a117ca273e28eac7db1))
* Release GitHub action ([#1078](https://github.com/jswebguru/private-gpt-medical/issues/1078)) ([75aa1da](https://github.com/jswebguru/private-gpt-medical/commit/75aa1daace6ecfa5e18063c92602e3ff396b00da))
* **scripts:** Wipe qdrant and obtain db Stats command ([#1783](https://github.com/jswebguru/private-gpt-medical/issues/1783)) ([03dbb54](https://github.com/jswebguru/private-gpt-medical/commit/03dbb5478d905cbb436a0359ac6aff0fddba95b0))
* **settings:** Configurable context_window and tokenizer ([#1437](https://github.com/jswebguru/private-gpt-medical/issues/1437)) ([9cc6bc2](https://github.com/jswebguru/private-gpt-medical/commit/9cc6bc2081275ea599634810e0747a3eec9b614e))
* **settings:** Update default model to TheBloke/Mistral-7B-Instruct-v0.2-GGUF ([#1415](https://github.com/jswebguru/private-gpt-medical/issues/1415)) ([f4389bd](https://github.com/jswebguru/private-gpt-medical/commit/f4389bd3c90d51ed5b6a741bb213a352d35a822a))
* **ui:** add LLM mode to UI ([#1080](https://github.com/jswebguru/private-gpt-medical/issues/1080)) ([859cfc5](https://github.com/jswebguru/private-gpt-medical/commit/859cfc538e76f88e7e1d74097274c3e9e4294981))
* **ui:** Add Model Information to ChatInterface label ([67557a3](https://github.com/jswebguru/private-gpt-medical/commit/67557a3016b32071035b77e6dcd32a11d6b3fa5b))
* **ui:** add sources check to not repeat identical sources ([#1705](https://github.com/jswebguru/private-gpt-medical/issues/1705)) ([28a3f93](https://github.com/jswebguru/private-gpt-medical/commit/28a3f93da6a9330c1291e775c4f756aff8b8c449))
* **ui:** Allows User to Set System Prompt via "Additional Options" in Chat Interface ([#1353](https://github.com/jswebguru/private-gpt-medical/issues/1353)) ([c68e73d](https://github.com/jswebguru/private-gpt-medical/commit/c68e73dddaca36553792a6c9222a7b9a481d1444))
* **UI:** Faster startup and document listing ([#1763](https://github.com/jswebguru/private-gpt-medical/issues/1763)) ([ee7d197](https://github.com/jswebguru/private-gpt-medical/commit/ee7d197cb876cf2e5522e0bf807cd7b9d4545b50))
* **ui:** maintain score order when curating sources ([#1643](https://github.com/jswebguru/private-gpt-medical/issues/1643)) ([a61713a](https://github.com/jswebguru/private-gpt-medical/commit/a61713a2f370513622900f73ad65998ae7f8296b))
* **ui:** make chat area stretch to fill the screen ([#1397](https://github.com/jswebguru/private-gpt-medical/issues/1397)) ([813c635](https://github.com/jswebguru/private-gpt-medical/commit/813c6353460c24ed3791d50250ad6e2730ecd842))
* **UI:** Select file to Query or Delete + Delete ALL ([#1612](https://github.com/jswebguru/private-gpt-medical/issues/1612)) ([aea75ad](https://github.com/jswebguru/private-gpt-medical/commit/aea75adc403760006979c99933c059e21f9704f6))
* unify settings for vector and nodestore connections to PostgreSQL ([#1730](https://github.com/jswebguru/private-gpt-medical/issues/1730)) ([cc23d72](https://github.com/jswebguru/private-gpt-medical/commit/cc23d7253ee0a03b4c41698ccf2673b0d11cbf9e))
* Upgrade to LlamaIndex to 0.10 ([#1663](https://github.com/jswebguru/private-gpt-medical/issues/1663)) ([31de5dd](https://github.com/jswebguru/private-gpt-medical/commit/31de5dd1633b50dc03911f840f28cb213df97e9b))
* **vectorstore:** Add clickhouse support as vectore store ([#1883](https://github.com/jswebguru/private-gpt-medical/issues/1883)) ([eed299f](https://github.com/jswebguru/private-gpt-medical/commit/eed299f34fa804f08b5da8a01525af11381ed5e1))
* **Vector:** support pgvector ([#1624](https://github.com/jswebguru/private-gpt-medical/issues/1624)) ([ef57ae6](https://github.com/jswebguru/private-gpt-medical/commit/ef57ae63aac7ab1a2fa00540c339a965ca74c061))
* wipe per storage type ([#1772](https://github.com/jswebguru/private-gpt-medical/issues/1772)) ([0d082dc](https://github.com/jswebguru/private-gpt-medical/commit/0d082dcc780b8880be7df377f0a848a2f3765538))


### Bug Fixes

* "no such group" error in Dockerfile, added docx2txt and cryptography deps ([#1841](https://github.com/jswebguru/private-gpt-medical/issues/1841)) ([9c423f5](https://github.com/jswebguru/private-gpt-medical/commit/9c423f56cbc1860dedaf9272c26fcc7809473be6))
* 294 (tested) ([4564c8d](https://github.com/jswebguru/private-gpt-medical/commit/4564c8d9eb4e9259521aa47884b7fe83f7393fa6))
* Add `TARGET_SOURCE_CHUNKS` to `example.env` ([fb36283](https://github.com/jswebguru/private-gpt-medical/commit/fb3628320d57e356620efe169d2586d1761af730))
* Adding an LLM param to fix broken generator from llamacpp ([#1519](https://github.com/jswebguru/private-gpt-medical/issues/1519)) ([6fcdfaf](https://github.com/jswebguru/private-gpt-medical/commit/6fcdfafd09978807f9f3415759388b0713b18fd1))
* chromadb max batch size ([#1087](https://github.com/jswebguru/private-gpt-medical/issues/1087)) ([b6c9f68](https://github.com/jswebguru/private-gpt-medical/commit/b6c9f68a080acc3328eaa2b965fa448f9a5179ca))
* **deploy:** fix local and external dockerfiles ([6976d0e](https://github.com/jswebguru/private-gpt-medical/commit/6976d0e1b37cd49dbe23589489271b7d99fef3fb))
* Disable Chroma Telemetry ([8009dd4](https://github.com/jswebguru/private-gpt-medical/commit/8009dd40cf52d6d66644b6dbc56ed7c361a0cb19))
* Docker and sagemaker setup ([#1118](https://github.com/jswebguru/private-gpt-medical/issues/1118)) ([aab4edb](https://github.com/jswebguru/private-gpt-medical/commit/aab4edb3e83d9ee6577668b29f875309370a1aef))
* **docker:** docker broken copy ([#1419](https://github.com/jswebguru/private-gpt-medical/issues/1419)) ([f0f0f28](https://github.com/jswebguru/private-gpt-medical/commit/f0f0f2889b9751e517d87fe4ba3026c8af35c2be))
* **docs:** Fix concepts.mdx referencing to installation page ([#1779](https://github.com/jswebguru/private-gpt-medical/issues/1779)) ([d9b69fe](https://github.com/jswebguru/private-gpt-medical/commit/d9b69feb7cc6a1c1aa002ee01a9b404ce9178a76))
* **docs:** Minor documentation amendment ([#1739](https://github.com/jswebguru/private-gpt-medical/issues/1739)) ([24c686e](https://github.com/jswebguru/private-gpt-medical/commit/24c686e13056c93e86d1a4e84fff8ca5bbf6b856))
* **docs:** Update installation.mdx ([#1866](https://github.com/jswebguru/private-gpt-medical/issues/1866)) ([b3a2f5d](https://github.com/jswebguru/private-gpt-medical/commit/b3a2f5d59a303bbcf9b3eb1233eb1a8deec1539f))
* **docs:** Update quickstart doc and set version in pyproject.toml to 0.2.0 ([12ae843](https://github.com/jswebguru/private-gpt-medical/commit/12ae8432eee961a1303035f6ed809509c0b95683))
* fix pytorch version to avoid wheel bug ([#1123](https://github.com/jswebguru/private-gpt-medical/issues/1123)) ([1e6cf93](https://github.com/jswebguru/private-gpt-medical/commit/1e6cf93c69c6761a947358bc1528a8551c06d67c))
* Fixed docker-compose ([#1758](https://github.com/jswebguru/private-gpt-medical/issues/1758)) ([f82c86d](https://github.com/jswebguru/private-gpt-medical/commit/f82c86df267f7815321715fc576a8aed9cb9086b))
* **ingest:** update script label ([#1770](https://github.com/jswebguru/private-gpt-medical/issues/1770)) ([9ff941f](https://github.com/jswebguru/private-gpt-medical/commit/9ff941f2c6d63d71231293a425400586cd977e6b))
* **LLM:** mistral ignoring assistant messages ([#1954](https://github.com/jswebguru/private-gpt-medical/issues/1954)) ([849466a](https://github.com/jswebguru/private-gpt-medical/commit/849466ae1c29af0e712bd86985c38fd285eddd99))
* **llm:** special tokens and leading space ([#1831](https://github.com/jswebguru/private-gpt-medical/issues/1831)) ([e3e5bd6](https://github.com/jswebguru/private-gpt-medical/commit/e3e5bd6555e51658bcb9ac3557248f2c1f7786b4))
* make docs more visible ([#1081](https://github.com/jswebguru/private-gpt-medical/issues/1081)) ([0f43f31](https://github.com/jswebguru/private-gpt-medical/commit/0f43f31ca0b7c99ff1869b67e339bf5e7aa0e25f))
* make embedding_api_base match api_base when on docker ([#1859](https://github.com/jswebguru/private-gpt-medical/issues/1859)) ([7e89488](https://github.com/jswebguru/private-gpt-medical/commit/7e89488d430187362259bf27e39c0ccf8311b006))
* minor bug in chat stream output - python error being serialized ([#1449](https://github.com/jswebguru/private-gpt-medical/issues/1449)) ([bdeeb07](https://github.com/jswebguru/private-gpt-medical/commit/bdeeb0755edf5ccd8df61baf851f91c0cc87f151))
* Remove global state ([#1216](https://github.com/jswebguru/private-gpt-medical/issues/1216)) ([ee8a8af](https://github.com/jswebguru/private-gpt-medical/commit/ee8a8afe2a013fdaf75a878e0cc7c44dc882a312))
* Replacing unsafe `eval()` with `json.loads()` ([#1890](https://github.com/jswebguru/private-gpt-medical/issues/1890)) ([bc0482b](https://github.com/jswebguru/private-gpt-medical/commit/bc0482b819931b6ec56fb7fc6fc081939bde1b6a))
* sagemaker config and chat methods ([#1142](https://github.com/jswebguru/private-gpt-medical/issues/1142)) ([5bc9567](https://github.com/jswebguru/private-gpt-medical/commit/5bc9567375c052cc8f7ae3fc2297b62b4d5bcf75))
* **settings:** correct yaml multiline string ([#1403](https://github.com/jswebguru/private-gpt-medical/issues/1403)) ([0b33c71](https://github.com/jswebguru/private-gpt-medical/commit/0b33c7100505333a4600170803b381432a5214e7))
* **settings:** enable cors by default so it will work when using ts sdk (spa) ([#1925](https://github.com/jswebguru/private-gpt-medical/issues/1925)) ([a922dc8](https://github.com/jswebguru/private-gpt-medical/commit/a922dc86040936c0084affa5763c23c2b713e750))
* **settings:** set default tokenizer to avoid running make setup fail ([#1709](https://github.com/jswebguru/private-gpt-medical/issues/1709)) ([26e77d8](https://github.com/jswebguru/private-gpt-medical/commit/26e77d81475f8c8a8997eda3755290d63d720bf7))
* **tests:** load the test settings only when running tests ([2be4e2e](https://github.com/jswebguru/private-gpt-medical/commit/2be4e2e64bf86694b135d39882f7552e06609ebb))
* typo in README.md ([#1091](https://github.com/jswebguru/private-gpt-medical/issues/1091)) ([de62169](https://github.com/jswebguru/private-gpt-medical/commit/de621696d444f8d00d96b8e0304ef3879f527d0a))
* **UI:** Updated ui.py. Frees up the CPU to not be bottlenecked. ([c9dca90](https://github.com/jswebguru/private-gpt-medical/commit/c9dca905fc8f9b611ff1d6a2075f273878c7448f))
* Windows 11 failing to auto-delete tmp file ([#1260](https://github.com/jswebguru/private-gpt-medical/issues/1260)) ([a3bcfbc](https://github.com/jswebguru/private-gpt-medical/commit/a3bcfbc3c61de62f97dc452cd0a0a68da836fddb))
* Windows permission error on ingest service tmp files ([#1280](https://github.com/jswebguru/private-gpt-medical/issues/1280)) ([d5913bc](https://github.com/jswebguru/private-gpt-medical/commit/d5913bc52530da4e7f85788c9c2b19e73b5bff15))


### Miscellaneous Chores

* Initial version ([9a620e1](https://github.com/jswebguru/private-gpt-medical/commit/9a620e1407de85c2df875e90fca7661bdb27a0ab))

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
