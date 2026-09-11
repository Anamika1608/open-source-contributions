<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/title-dark.svg">
  <img src="assets/title-light.svg" alt="Open Source Contributions" height="48">
</picture>

1. [**urunc**](https://github.com/urunc-dev/urunc) (Go) &nbsp;·&nbsp; 7 pull requests
2. [**consul democracy**](https://github.com/consuldemocracy/consuldemocracy) (Ruby on Rails) &nbsp;·&nbsp; 3 pull requests
3. [**dataframe**](https://github.com/DataHaskell/dataframe) (Haskell) &nbsp;·&nbsp; 3 pull requests, 1 issue
4. [**p4lang**](https://github.com/p4lang) (GitHub Actions) &nbsp;·&nbsp; 2 pull requests
5. [**cilium.io**](https://github.com/cilium/cilium.io) (React) &nbsp;·&nbsp; 13 pull requests

<br>

<h3><img src="https://github.com/urunc-dev.png" width="28" align="center" alt=""> &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="assets/h-urunc-dark.svg"><img src="assets/h-urunc-light.svg" alt="urunc" align="center"></picture></h3>

<img src="assets/lang-go.svg" alt="Go">

- **Project:** OCI-compatible container runtime that boots unikernels as containers on Firecracker, QEMU, and Cloud Hypervisor.
- **My work:** Built the control-socket layer for all three monitors: API boot modes, graceful shutdown, and the guest-side handler in urunit.

| Pull request | Status |
|:--|:--|
| **[Expose a configurable control socket for each monitor](https://github.com/urunc-dev/urunc/pull/850)** | Approved |
| **[Firecracker: API boot mode over the control socket](https://github.com/urunc-dev/urunc/pull/809)** | Open |
| **[QEMU: API boot mode over the QMP control socket](https://github.com/urunc-dev/urunc/pull/841)** | Open |
| **[Cloud Hypervisor: API boot mode over the REST API socket](https://github.com/urunc-dev/urunc/pull/847)** | Open |
| **[Graceful shutdown over the control socket](https://github.com/urunc-dev/urunc/pull/869)** | Open |
| **[React to guest shutdown events, guest side](https://github.com/nubificus/urunit/pull/15)** | Open |
| **[Close tap device fd after creation](https://github.com/urunc-dev/urunc/pull/831)** | Merged |

<br>

<h3><img src="https://github.com/consuldemocracy.png" width="28" align="center" alt=""> &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="assets/h-consul-dark.svg"><img src="assets/h-consul-light.svg" alt="consul democracy" align="center"></picture></h3>

<img src="assets/lang-rails.svg" alt="Ruby on Rails">

- **Project:** Citizen participation platform that cities worldwide use for proposals, debates, and participatory budgeting.
- **My work:** Added enterprise single sign-on: SAML and OIDC authentication, plus per-install SAML settings.

| Pull request | Status |
|:--|:--|
| **[Add support for SAML authentication](https://github.com/consuldemocracy/consuldemocracy/pull/6010)** | Merged |
| **[Add support for OIDC authentication](https://github.com/consuldemocracy/consuldemocracy/pull/6046)** | Merged |
| **[Allow additional settings in SAML configuration](https://github.com/consuldemocracy/consuldemocracy/pull/6069)** | Merged |

<br>

<h3><img src="https://github.com/DataHaskell.png" width="28" align="center" alt=""> &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="assets/h-dataframe-dark.svg"><img src="assets/h-dataframe-light.svg" alt="dataframe" align="center"></picture></h3>

<img src="assets/lang-haskell.svg" alt="Haskell">

- **Project:** Fast, type-safe dataframe library for Haskell with CSV and Parquet readers.
- **My work:** Found and fixed a join bug for missing key columns, and documented and tested the Parquet read options.

| Pull request | Status |
|:--|:--|
| **[Fix joins for missing key columns](https://github.com/DataHaskell/dataframe/pull/187)** | Merged |
| **[Fix alignment in iris tutorial introduction](https://github.com/DataHaskell/dataframe/pull/185)** | Merged |
| **[Left and right joins should be swapped](https://github.com/DataHaskell/dataframe/issues/163)** **(issue)** | Closed |
| **[Document and test safeColumns in ParquetReadOptions](https://github.com/DataHaskell/dataframe/pull/190)** | Merged |

<br>

<h3><img src="https://github.com/p4lang.png" width="28" align="center" alt=""> &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="assets/h-p4lang-dark.svg"><img src="assets/h-p4lang-light.svg" alt="p4lang" align="center"></picture></h3>

<img src="assets/lang-github-actions.svg" alt="GitHub Actions">

- **Project:** Reference software switch (behavioral-model) and packet test framework (ptf) for P4 programmable data planes.
- **My work:** Automated the monthly release workflows for both repositories with GitHub Actions.

| Pull request | Status |
|:--|:--|
| **[Add automated monthly release workflows](https://github.com/p4lang/behavioral-model/pull/1353)** | Merged |
| **[Add automated monthly release workflows](https://github.com/p4lang/ptf/pull/233)** | Merged |

<br>

<h3><img src="https://github.com/cilium.png" width="28" align="center" alt=""> &nbsp;<picture><source media="(prefers-color-scheme: dark)" srcset="assets/h-cilium-dark.svg"><img src="assets/h-cilium-light.svg" alt="cilium.io" align="center"></picture></h3>

<img src="assets/lang-react.svg" alt="React">

- **Project:** Website for Cilium, the eBPF-based networking, observability, and security project.
- **My work:** Shipped the dark theme end to end, then fixed the pages it touched and a run of mobile layout bugs.

| Pull request | Status |
|:--|:--|
| **[Horizontal scrolling on adopters route](https://github.com/cilium/cilium.io/pull/654)** | Merged |
| **[Blog thumbnail images on home page](https://github.com/cilium/cilium.io/pull/664)** | Merged |
| **[Add dark theme](https://github.com/cilium/cilium.io/pull/667)** | Merged |
| **[Dark theme text on blog pages](https://github.com/cilium/cilium.io/pull/675)** | Merged |
| **[Navbar on mobile view](https://github.com/cilium/cilium.io/pull/680)** | Merged |
| **[404 page colors in dark theme](https://github.com/cilium/cilium.io/pull/696)** | Merged |
| **[Card overflow on adopters route in mobile view](https://github.com/cilium/cilium.io/pull/706)** | Merged |
| **[useDarkMode hook applies dark theme](https://github.com/cilium/cilium.io/pull/719)** | Merged |
| **[Add dark theme to telling-story form page](https://github.com/cilium/cilium.io/pull/722)** | Merged |
| **[Debounced loader animation on blog search](https://github.com/cilium/cilium.io/pull/737)** | Merged |
| **[KodeKloud logo overflow on enterprise page in mobile view](https://github.com/cilium/cilium.io/pull/738)** | Merged |
| **[Image flicker on reloading newsletter page](https://github.com/cilium/cilium.io/pull/745)** | Merged |
| **[Brand hero image and top-banner text](https://github.com/cilium/cilium.io/pull/755)** | Merged |

<br>
