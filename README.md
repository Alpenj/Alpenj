# Hyungjoo Jeon · 전형주

---

### About

I earned a Master of Engineering (M.Eng.) in Advanced Device Technology and spent two years and four months researching optical-device packaging. I then planned web services for three years and nine months and led a full-stack web development team for one year and four months.

We built SWEEPICK as a four-person team in Dongguk University’s DAPIER Physical AI program. I made the simulation training data, integrated the physical robot, and connected the mobile base and both arms through ROS 2. I developed and evaluated the ACT model with a teammate.

We froze the epoch 30 model and ran it once per position in simulation. The robot completed **132/143** runs overall and **27/31** at Test positions held out from training. On November 1, 2026, the physical robot picked up an object, carried and placed it, and returned to its starting pose for the first time without human intervention.

<details>
<summary>국문 소개</summary>

차세대소자공학 석사를 마치고 2년 4개월 동안 광소자 패키징을 연구했습니다. 이후 웹서비스를 3년 9개월 기획했고, 풀스택 웹 개발팀장으로 1년 4개월 일했습니다.

동국대 DAPIER Physical AI 과정에서 4인 팀으로 SWEEPICK을 만들었습니다. 저는 시뮬레이션 학습 데이터를 만들고 실물 로봇을 통합했습니다. 이동 베이스와 양팔을 ROS 2로 연결했고, ACT 모델은 팀원 한 명과 함께 개발하고 평가했습니다.

epoch 30 모델을 고정해 시뮬레이션에서 위치마다 한 번씩 실행했습니다. 전체 **132/143곳**, 학습에 쓰지 않은 Test 위치 **27/31곳**에서 로봇이 작업을 마쳤습니다. 2026년 11월 1일에는 실물 로봇이 사람 개입 없이 물체를 집어 옮겨 놓고 시작 자세로 돌아오는 데 처음 성공했습니다.

[VERA](https://vera.builders/)는 회사에서 개발한 인테리어·건설 자재 관리 플랫폼입니다. 저는 AI 상담·자재·리스크 API를 만들고, AI가 응답하지 않을 때는 미리 정한 규칙으로 처리하도록 했습니다.

</details>

### Selected work

I completed the first DAPIER Physical AI cohort at Dongguk University (656 hours, July 6–November 4, 2026).

- **[SWEEPICK](https://github.com/Alpenj/sweepick)** (August–November 2026). We built a low-cost mobile robot with two arms to pick up objects before cleaning. In RoboTwin, I attempted demonstrations at 143 positions and kept 113 successful trajectories. I rebuilt the physical workspace in Isaac Sim to try Sim-to-Real transfer. On the robot, I automated grasp demonstrations and converted the recordings into ACT training episodes. I also built and maintained a dashboard that showed start and stop responses and let me compare target and measured joint positions. We tested the model at 80 grid points and 63 cell centers in simulation. On hardware, we recorded 7/10, 8/10 and 7/10 successful grasps across three objects. [Evaluation setup](https://github.com/Alpenj/sweepick/blob/main/docs/CUSTOM_ACT_V1_KO.md)
- **[deepThinkCar](https://github.com/Alpenj/DAPIER/tree/main/mini-projects/deepThinkCar_mini)**. I added stop conditions and measured a candidate steering model. On the same split, steering MAE fell from 14.93° to 4.93°. I kept the candidate in evaluation because the test covered a narrow set of conditions.
- **[SyncGuard](https://julianjeonresume.netlify.app/#project-syncguard)**. I checked whether sensor timestamps lined up before training. On synthetic data with jitter and dropped samples, valid alignment rose from 33.6% to 98.2% and p95 skew fell from 46.7 to 3.3 ms.
- **[ROS 2 practice](https://github.com/Alpenj/DAPIER/tree/main/ros2-practice)**. I used URDF, TF, SLAM and Nav2 on Jazzy and tracked down issues during the move from Humble to Jazzy.
- **[VERA](https://vera.builders/)**. I worked on this company project for managing materials in interior design and construction. I used coding agents to build it in two weeks, added rule-based fallbacks to the LLM APIs, and set up tests with Vitest and Playwright.
- **Earlier work.** I led full-stack development and automated workflows with React/Next.js, Supabase and Playwright. I also planned web services and worked in optical transceiver R&D.

---

### 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1F6FEB?style=flat)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=flat&logo=nvidia&logoColor=white)
![LeRobot](https://img.shields.io/badge/LeRobot_%2F_ACT-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### Tools and workflow

| Topic | Details |
|---|---|
| 📍 | Korea · completed Dongguk University’s DAPIER Physical AI program on Nov 4, 2026 |
| 🔧 | Python, C++, ROS 2 (topics, TF, URDF/RViz), Nav2 basics, MuJoCo, Isaac Sim, RoboTwin, LeRobot / ACT, PyTorch, OpenCV, Linux |
| 🧪 | For SWEEPICK, I prepared ACT data, tested the model with a teammate, and connected the SO-101 arms to the mobile base over ROS 2. |
| 🤖 | When I use Claude Code or Codex, I write down what to build and how I’ll check it, then review the code and run tests. I’ve added rule-based fallbacks to LLM features and built agents to automate personal tasks. |
| 📚 | [Portfolio](https://julianjeonresume.netlify.app/) · [SWEEPICK](https://github.com/Alpenj/sweepick) · [mini projects & practice](https://github.com/Alpenj/DAPIER) |

---

### 🌐 Open Source

I fix Python projects that run into encoding and file-handling bugs on Windows. I reproduce each bug on Korean Windows (cp949) and add a test that catches it.

| Project | Change | Status |
|---|---|---|
| [jupytext](https://github.com/jupytext/jupytext/pull/1679) | Use UTF-8 for the temporary files exchanged with marimo | [![PR 1679 status](https://img.shields.io/github/pulls/detail/state/jupytext/jupytext/1679?style=flat&label=)](https://github.com/jupytext/jupytext/pull/1679) |
| [Panel](https://github.com/holoviz/panel/pull/9036) | Read and write user files as UTF-8 | [![PR 9036 status](https://img.shields.io/github/pulls/detail/state/holoviz/panel/9036?style=flat&label=)](https://github.com/holoviz/panel/pull/9036) |
| [commitizen](https://github.com/commitizen-tools/commitizen/pull/2119) | Explicit encodings in `cz commit --edit` and `cz init` | [![PR 2119 status](https://img.shields.io/github/pulls/detail/state/commitizen-tools/commitizen/2119?style=flat&label=)](https://github.com/commitizen-tools/commitizen/pull/2119) |
| [huggingface_hub](https://github.com/huggingface/huggingface_hub/pull/5310) | Read `--filter-from` files as UTF-8 | [![PR 5310 status](https://img.shields.io/github/pulls/detail/state/huggingface/huggingface_hub/5310?style=flat&label=)](https://github.com/huggingface/huggingface_hub/pull/5310) |
| [Locust](https://github.com/locustio/locust/pull/3595) | Read locustfiles as UTF-8 before sending them to workers | [![PR 3595 status](https://img.shields.io/github/pulls/detail/state/locustio/locust/3595?style=flat&label=)](https://github.com/locustio/locust/pull/3595) |
| [python-semantic-release](https://github.com/python-semantic-release/python-semantic-release/pull/1505) | Read the previous changelog as UTF-8 | [![PR 1505 status](https://img.shields.io/github/pulls/detail/state/python-semantic-release/python-semantic-release/1505?style=flat&label=)](https://github.com/python-semantic-release/python-semantic-release/pull/1505) |
| [Salt](https://github.com/saltstack/salt/pull/70776) | Fix `network.connect` always failing with `proto=udp` | [![PR 70776 status](https://img.shields.io/github/pulls/detail/state/saltstack/salt/70776?style=flat&label=)](https://github.com/saltstack/salt/pull/70776) |
| [xonsh](https://github.com/xonsh/xonsh/pull/6668) | Read the RC file, xontrib sources and the stash log as UTF-8 | [![PR 6668 status](https://img.shields.io/github/pulls/detail/state/xonsh/xonsh/6668?style=flat&label=)](https://github.com/xonsh/xonsh/pull/6668) |
| [Apprise](https://github.com/caronc/apprise/pull/1887) | Read Discord, Slack, Telegram and Workflows templates as UTF-8 | [![PR 1887 status](https://img.shields.io/github/pulls/detail/state/caronc/apprise/1887?style=flat&label=)](https://github.com/caronc/apprise/pull/1887) |
| [pipenv](https://github.com/pypa/pipenv/pull/6786) | Keep the downloaded requirements file for `pipenv install -r <url>` | [![PR 6786 status](https://img.shields.io/github/pulls/detail/state/pypa/pipenv/6786?style=flat&label=)](https://github.com/pypa/pipenv/pull/6786) |
| [OpenJarvis](https://github.com/open-jarvis/OpenJarvis/pull/1273) | Format digest dates without glibc-only `strftime` flags | [![PR 1273 status](https://img.shields.io/github/pulls/detail/state/open-jarvis/OpenJarvis/1273?style=flat&label=)](https://github.com/open-jarvis/OpenJarvis/pull/1273) |
| [mycli](https://github.com/dbcli/mycli/pull/2434) | Read and write `--batch` and `--checkpoint` files as UTF-8 | [![PR 2434 status](https://img.shields.io/github/pulls/detail/state/dbcli/mycli/2434?style=flat&label=)](https://github.com/dbcli/mycli/pull/2434) |
| [trimesh](https://github.com/mikedh/trimesh/pull/2678) | Close the meshio temporary file before reading it on Windows | [![PR 2678 status](https://img.shields.io/github/pulls/detail/state/mikedh/trimesh/2678?style=flat&label=)](https://github.com/mikedh/trimesh/pull/2678) |
| [Harlequin](https://github.com/tconbeer/harlequin/pull/1238) | Read DuckDB and SQLite init scripts as UTF-8 | [![PR 1238 status](https://img.shields.io/github/pulls/detail/state/tconbeer/harlequin/1238?style=flat&label=)](https://github.com/tconbeer/harlequin/pull/1238) |
| [dirsearch](https://github.com/maurosoria/dirsearch/pull/1778) | Read wordlists and URL/proxy list files as UTF-8 | [![PR 1778 status](https://img.shields.io/github/pulls/detail/state/maurosoria/dirsearch/1778?style=flat&label=)](https://github.com/maurosoria/dirsearch/pull/1778) |
| [ComfyUI-Manager](https://github.com/Comfy-Org/ComfyUI-Manager/pull/3520) | Read a node pack's `requirements.txt` with the encoding fallback when installing | [![PR 3520 status](https://img.shields.io/github/pulls/detail/state/Comfy-Org/ComfyUI-Manager/3520?style=flat&label=)](https://github.com/Comfy-Org/ComfyUI-Manager/pull/3520) |
| [manga-image-translator](https://github.com/zyddnys/manga-image-translator/pull/1189) | Read and write translation text files as UTF-8 | [![PR 1189 status](https://img.shields.io/github/pulls/detail/state/zyddnys/manga-image-translator/1189?style=flat&label=)](https://github.com/zyddnys/manga-image-translator/pull/1189) |
| [semantic-router](https://github.com/aurelio-labs/semantic-router/pull/860) | Read and write router YAML/JSON files as UTF-8 | [![PR 860 status](https://img.shields.io/github/pulls/detail/state/aurelio-labs/semantic-router/860?style=flat&label=)](https://github.com/aurelio-labs/semantic-router/pull/860) |
| [thonny](https://github.com/thonny/thonny/pull/3981) | Read `pyvenv.cfg` as UTF-8 so venvs under non-ASCII paths work on Windows | [![PR 3981 status](https://img.shields.io/github/pulls/detail/state/thonny/thonny/3981?style=flat&label=)](https://github.com/thonny/thonny/pull/3981) |
| [ursina](https://github.com/pokepetter/ursina/pull/855) | Read `.obj` files as UTF-8 so non-ASCII material names keep their colors | [![PR 855 status](https://img.shields.io/github/pulls/detail/state/pokepetter/ursina/855?style=flat&label=)](https://github.com/pokepetter/ursina/pull/855) |
| [Flexget](https://github.com/Flexget/Flexget/pull/5326) | Read template files as UTF-8 in the `flexget templates` command | [![PR 5326 status](https://img.shields.io/github/pulls/detail/state/Flexget/Flexget/5326?style=flat&label=)](https://github.com/Flexget/Flexget/pull/5326) |
| [ursina](https://github.com/pokepetter/ursina/pull/856) | Read `ursina_settings.py` as UTF-8 so settings with non-ASCII text load | [![PR 856 status](https://img.shields.io/github/pulls/detail/state/pokepetter/ursina/856?style=flat&label=)](https://github.com/pokepetter/ursina/pull/856) |
| [syncplay](https://github.com/Syncplay/syncplay/pull/834) | Read and write playlist files (`.m3u8`, `.txt`) as UTF-8 | [![PR 834 status](https://img.shields.io/github/pulls/detail/state/Syncplay/syncplay/834?style=flat&label=)](https://github.com/Syncplay/syncplay/pull/834) |
| [OpenShot](https://github.com/OpenShot/openshot-qt/pull/6266) | Read EDL files as UTF-8 when importing, matching the EDL export | [![PR 6266 status](https://img.shields.io/github/pulls/detail/state/OpenShot/openshot-qt/6266?style=flat&label=)](https://github.com/OpenShot/openshot-qt/pull/6266) |

---

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-genuine2027%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:genuine2027@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white)](https://www.linkedin.com/in/hyungjoo-jeon/)
[![Portfolio](https://img.shields.io/badge/Portfolio-julianjeonresume-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://julianjeonresume.netlify.app/)
