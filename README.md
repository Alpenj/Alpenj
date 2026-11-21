# Hi there, I'm Hyungjoo 👋

---

### 🤖 About Me

#### Physical AI · Robotics software | Imitation-learning data · Simulation · Sim-to-Real | Python · C++ · ROS 2 · MuJoCo<br>
I earned an M.S. in Advanced Device Technology and worked in optical R&D, web planning and full-stack development as a team lead before moving into robotics software.<br>
I work on training data in simulation and getting learned policies to run on real robots. For each test, I record the setup alongside the result.

  🎓 Physical AI program (DAPIER Cohort 1), Dongguk University · 656 hours · Jul 6–Nov 4, 2026 · completed<br>
  🧹 [SWEEPICK](https://github.com/Alpenj/sweepick) (team of 4): We built a low-cost mobile robot with two arms to clear objects from the floor. I led simulation data and domain randomization, Sim-to-Real integration and the ROS 2 handoff between the base and arms. I also co-developed the ACT policy. Our first unassisted full run on hardware was on Nov 1, 2026. Grasp results on hardware were 7/10, 8/10 and 7/10 across three objects. In simulation, the mid-training epoch-30 checkpoint was frozen before the full evaluation. It completed 132/143 one-trial locations across 80 grid points and 63 cell centers, including 27/31 held-out test locations. [Evaluation setup](https://github.com/Alpenj/sweepick/blob/main/docs/CUSTOM_ACT_V1_KO.md).<br>
  🚗 [deepThinkCar](https://github.com/Alpenj/DAPIER/tree/main/mini-projects/deepThinkCar_mini): Added stop conditions and evaluated a candidate steering model. Steering MAE fell from 14.93° to 4.93° on the same split. I held off on using the model in the car because the evaluation was narrow.<br>
  ⏱️ [SyncGuard](https://julianjeonresume.netlify.app/#project-syncguard): Checked timestamp alignment before training. On synthetic data with jitter and dropped samples, valid alignment rose from 33.6% to 98.2% and p95 skew fell from 46.7 to 3.3 ms.<br>
  🧭 [ROS 2 practice](https://github.com/Alpenj/DAPIER/tree/main/ros2-practice): Worked with URDF, TF, SLAM and Nav2 on Jazzy and diagnosed issues while migrating from Humble to Jazzy.<br>
  🏗️ [VERA](https://vera.builders/): interior/construction SCM platform built with coding agents in two weeks; LLM APIs with rule-based fallbacks and a Vitest/Playwright QA pipeline.<br>
  ⚽ [soccerhelper](https://github.com/Alpenj/soccerhelper): web/mobile MVP for amateur football teams (Next.js · Expo · Supabase).<br>
  💼 Earlier work: full-stack web team lead (React/Next.js, Supabase, Playwright automation), freelance full-stack (NestJS, payments and webhooks, GitHub Actions, Docker/EC2), optical transceiver R&D.

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

### 🧭 Now & Next

| Topic | Details |
|---|---|
| 📍 | Korea · completed the Physical AI program on Nov 4, 2026 · looking for robotics software roles in imitation learning, simulation, Sim-to-Real and robot integration |
| 🔧 | Hands-on: Python, C++, ROS 2 (topics, TF, URDF/RViz), Nav2 basics, MuJoCo, Isaac Sim, RoboTwin, LeRobot / ACT, PyTorch, OpenCV, Linux |
| 🧪 | Recent work: dual-arm ACT data and evaluation, Sim-to-Real hand-off on SO-101 arms, ROS 2 base↔arm interface |
| 🤖 | I give Claude Code and Codex task specs and acceptance criteria, then verify the code with tests. I also build LLM features with rule-based fallbacks and agents for personal automation. |
| 📚 | Start here: [portfolio](https://julianjeonresume.netlify.app/) · [SWEEPICK](https://github.com/Alpenj/sweepick) · [mini projects & practice](https://github.com/Alpenj/DAPIER) |

---

### 🌐 Open Source

Windows bug fixes in widely used Python projects. I reproduce each bug on Korean Windows (cp949) and add a regression test that fails before the fix.

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
| [SABnzbd](https://github.com/sabnzbd/sabnzbd/pull/3693) | Read the password file as UTF-8, with a code page fallback | [![PR 3693 status](https://img.shields.io/github/pulls/detail/state/sabnzbd/sabnzbd/3693?style=flat&label=)](https://github.com/sabnzbd/sabnzbd/pull/3693) |
| [dirsearch](https://github.com/maurosoria/dirsearch/pull/1778) | Read wordlists and URL/proxy list files as UTF-8 | [![PR 1778 status](https://img.shields.io/github/pulls/detail/state/maurosoria/dirsearch/1778?style=flat&label=)](https://github.com/maurosoria/dirsearch/pull/1778) |
| [ComfyUI-Manager](https://github.com/Comfy-Org/ComfyUI-Manager/pull/3520) | Read a node pack's `requirements.txt` with the encoding fallback when installing | [![PR 3520 status](https://img.shields.io/github/pulls/detail/state/Comfy-Org/ComfyUI-Manager/3520?style=flat&label=)](https://github.com/Comfy-Org/ComfyUI-Manager/pull/3520) |
| [manga-image-translator](https://github.com/zyddnys/manga-image-translator/pull/1189) | Read and write translation text files as UTF-8 | [![PR 1189 status](https://img.shields.io/github/pulls/detail/state/zyddnys/manga-image-translator/1189?style=flat&label=)](https://github.com/zyddnys/manga-image-translator/pull/1189) |
| [semantic-router](https://github.com/aurelio-labs/semantic-router/pull/860) | Read and write router YAML/JSON files as UTF-8 | [![PR 860 status](https://img.shields.io/github/pulls/detail/state/aurelio-labs/semantic-router/860?style=flat&label=)](https://github.com/aurelio-labs/semantic-router/pull/860) |
| [thonny](https://github.com/thonny/thonny/pull/3981) | Read `pyvenv.cfg` as UTF-8 so venvs under non-ASCII paths work on Windows | [![PR 3981 status](https://img.shields.io/github/pulls/detail/state/thonny/thonny/3981?style=flat&label=)](https://github.com/thonny/thonny/pull/3981) |
| [ursina](https://github.com/pokepetter/ursina/pull/855) | Read `.obj` files as UTF-8 so non-ASCII material names keep their colors | [![PR 855 status](https://img.shields.io/github/pulls/detail/state/pokepetter/ursina/855?style=flat&label=)](https://github.com/pokepetter/ursina/pull/855) |
| [Flexget](https://github.com/Flexget/Flexget/pull/5326) | Read template files as UTF-8 in the `flexget templates` command | [![PR 5326 status](https://img.shields.io/github/pulls/detail/state/Flexget/Flexget/5326?style=flat&label=)](https://github.com/Flexget/Flexget/pull/5326) |

---

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-genuine2027%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:genuine2027@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white)](https://www.linkedin.com/in/hyungjoo-jeon/)
[![Portfolio](https://img.shields.io/badge/Portfolio-julianjeonresume-00C7B7?style=flat-square&logo=netlify&logoColor=white)](https://julianjeonresume.netlify.app/)
