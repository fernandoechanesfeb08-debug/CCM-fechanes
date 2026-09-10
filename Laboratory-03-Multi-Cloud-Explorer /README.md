# Laboratory 3 – Multi-Cloud Explorer

## Mission
CloudNova Technologies Cloud Evaluation Team task: research AWS, Microsoft Azure, and Google Cloud Platform, compare their services, and recommend the right platform for different business scenarios.

## Contents
- `aws-research.md` – AWS overview, infrastructure, console, core services, advantages, use cases
- `azure-research.md` – Azure overview, infrastructure, console, core services, advantages, use cases
- `gcp-research.md` – GCP overview, infrastructure, console, core services, advantages, use cases
- `cloud-platform-comparison.md` – side-by-side comparison table + equivalent-services table
- `client-recommendations.md` – per-client recommendations + decision matrix
- `reflection.md` – mission reflection
- `screenshots/` – evidence screenshots

---

## Checkpoint 7 – Linux Investigation (KillerCoda)

Launch a KillerCoda Playground and run the following commands, then record the results here:

| Info | Command | Result |
|---|---|---|
| Operating System | `cat /etc/os-release` or `uname -a` | *(<img width="892" height="30" alt="image" src="https://github.com/user-attachments/assets/67e94525-d041-49b5-ad28-1b116f2334c0" />
)* |
| CPU Information | `lscpu` or `cat /proc/cpuinfo` | *(<img width="1337" height="817" alt="image" src="https://github.com/user-attachments/assets/31676f89-7773-4cf7-9457-38a5c9cbb07a" />
)* |
| Memory | `free -h` | *(<img width="902" height="63" alt="image" src="https://github.com/user-attachments/assets/caf210c0-26b8-4b3a-bbf4-da77b1edf748" />
)* |
| Disk Space | `df -h` | *(<img width="676" height="127" alt="image" src="https://github.com/user-attachments/assets/b22be944-055f-40dd-987f-6d43d2bd4982" />
)* |

**Screenshot:** *(insert `;screenshots/killercoda-terminal.png` here)*

### If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?

- **AWS:** Amazon EC2 — the observed OS, CPU, memory, and disk specs map directly to choosing an equivalent EC2 instance type (e.g., a `t3`/`t4g` general-purpose instance sized to match the observed vCPU/RAM), with EBS volumes sized to match observed disk space.
- **Azure:** Azure Virtual Machines — an equivalent VM size (e.g., a B-series or D-series VM) can be chosen to match the observed CPU/memory, with a managed disk sized to match observed disk space.
- **GCP:** Compute Engine — a custom or predefined machine type can be configured to match the observed vCPU/RAM, with a persistent disk sized to match observed disk space.

*(Adjust the recommendation above once you have your actual KillerCoda output — match the instance/VM sizing to your real CPU, memory, and disk numbers.)*
