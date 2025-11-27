# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.0](https://github.com/lotusnoir/ansible-system_ldap_entries/compare/2.1.0...2.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`f2134bf`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/f2134bf3549cb847f0dbbf49089fcefe0d9aedf7)

## [2.1.0](https://github.com/lotusnoir/ansible-system_ldap_entries/compare/2.0.0...2.1.0) - 2025-11-17

### Commits

- update core and molecule [`72ac6b8`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/72ac6b82612be6d0f0f21213c19b088eebb1718a)
- add oraclelinux10 support + lint and core fixes [`dde451b`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/dde451b1a149d7bce434f15a2e9b6fcf52f6bbf1)

## [2.0.0](https://github.com/lotusnoir/ansible-system_ldap_entries/compare/1.0.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`dd1ef4f`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/dd1ef4f0dcb1e8724b1848d714e782a0d80fddf8)
- update core, molecule + gitlab-ci [`2afee14`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/2afee14ecfcf59f33b6eebd469b37717d8378596)
- fix lint [`6af3af3`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/6af3af342a99fb637fc113e3c58497bb7b663b48)
- fix molecule paralelism and little updates [`cf88589`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/cf885892a86ad186c116616663ebf5b6dcb703bc)
- fix [`bc4ba0f`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/bc4ba0f8b9da3a3a73d974d6df87584fe613dcd8)
- add support for ubuntu24 [`55dffa7`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/55dffa79f00983e06ec1530859f55fd0c811f35c)
- add version on molecule play image to maintain support on old release [`65d7356`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/65d73568ba7f63d52645e9d73b3f452833fec764)
- update molecule [`7924c41`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/7924c419d6da1eabe046f3f768f9962ded2bb4ee)
- add redhat 9 to default supported distrib [`7f0ca99`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/7f0ca99e69f5bba2b751482438f6c49e3aefb457)
- fix readme [`62b3391`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/62b3391b3931d3106fc000e5859a6cca2e77212d)

## [1.0.0](https://github.com/lotusnoir/ansible-system_ldap_entries/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`ad655c8`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/ad655c8f2a37451dea0ddae1b48a2cde9f205a64)
- update readme + precommit + include vars [`5e408fe`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/5e408fed593d4d7996bfc3775cd00da57e2fa14c)
- change import tasks to include in order to support facts on name [`72afa32`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/72afa32f4892f9abe756bd7f8a36231b5ce7fc07)
- Add recursive on delete than per single objects [`3b621b9`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/3b621b9db5f6f9beb3695a2ca27932ed6cedb6da)

## [0.2.0](https://github.com/lotusnoir/ansible-system_ldap_entries/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`53d38f4`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/53d38f4b1cd65ae4925713175694853f16fedd19)
- add condition to avoid creation on deletion [`582aad7`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/582aad7f562c00da66577d36ccc1e12401e5da6c)
- add delete feature [`301d257`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/301d25772c7d71c751ca21d303a080be739cc4f3)
- add galaxy id [`1257baa`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/1257baae4d35b1733b980e232fa5d01be253f245)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`0fbe484`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/0fbe484e3b7608560fc5c88d3077d9c4e37b0f24)
- add precommit for lint [`8afda20`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/8afda20df0a4d08371bf088d7a432f0c468726ff)
- fix checks [`4c4cb4b`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/4c4cb4be95e1e47ae557fda03dab4bab10c107ad)
- reduce checks with assert [`62309ae`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/62309aea4596daf940902114e71f4731163c84db)
- add new molecule all scenario [`a66309d`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/a66309da9e32390641087c07dbbb92b01c3c3714)
- split distro for molecule tests on ci [`326a301`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/326a3015c238d747defb81f5f0869098f733e587)
- update checks and Readme [`5c647bb`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/5c647bbf0b91925e9c86518853b9f27562141ea5)
- add molecule fix for ora9 [`3d9b7a0`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/3d9b7a030f9a6e7a5542b69c4b21c9042dd86043)
- add ora9 support [`ca620b6`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/ca620b6899ef16eb3282c45be0e0c089d97f9ee4)
- update vars [`cf8ee4f`](https://github.com/lotusnoir/ansible-system_ldap_entries/commit/cf8ee4f333c9fd39314a592462b9883487e447f8)
