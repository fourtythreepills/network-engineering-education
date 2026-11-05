# Network Engineering Education

Мой путь к сетевому инженеру в центре обработки данных: курсы, лабораторные работы и проекты. Всё, что я делаю руками, лежит здесь: конфиги, схемы, IP-планы, журналы поломок.

**Цель:** стажировка, затем работа сетевым инженером в ЦОД в Казахстане, дальше международные компании, рост до архитектора и руководства инфраструктурой. Параллельно хочу преподавать и объяснять сети другим.

## Как я учусь

- **Режим очереди.** Одновременно открыт один блок, следующий начинается только после закрытия предыдущего.
- **Каждый блок заканчивается проектом.** Проект выкладывается сюда: README, схема, IP-план, журнал поломок и их диагностики.
- **Блок закрыт,** когда проект сделан и я могу объяснить и продиагностировать его без подсказок.
- **Темп:** 2-4 часа в день, реально около 70%. Если не успеваю, режу всё, кроме текущего блока.
- **Английский каждый день:** документация, схемы, практика

## Проекты

| # | Проект | Статус |
|---|---|---|
| 1 | [Сеть офиса на два роутера](project-1-office-network/): VLSM, статическая маршрутизация, DHCP, имитация интернета | Готов |
| 2 | Enterprise Network: VLAN, inter-VLAN routing, OSPF, STP, EtherChannel, ACL, NAT | Впереди (CCNA 3) |
| 3 | Linux-сервер: SSH по ключам, firewall, Fail2ban, nginx reverse proxy, бэкап rsync + cron | Впереди |
| 4 | Мини-домен: Windows Server, Active Directory, GPO | Впереди |
| 5 | Security Audit: инвентаризация, nmap, отчёт | Впереди |
| 6 | Security Gateway: зоны Internet / DMZ / Internal, VPN | Впереди |
| 7 | Mini SOC на Wazuh: свои правила детектирования | Впереди |
| 8 | NOC-дашборд: Prometheus, Grafana, Alertmanager | Впереди |
| 9 | Infrastructure as Code: Ansible, Netmiko, бэкапы конфигов | Впереди |
| 10 | Leaf-spine фабрика в Containerlab с BGP и схема ЦОД | Впереди |
| 11 | EVPN-VXLAN фабрика: VRF, отказ линка и узла | Позже |
| 12-15 | Cloud и Terraform, Docker и DevSecOps, MSSP MVP, сеть GPU-кластера (InfiniBand vs RoCEv2) | Позже |

## Роадмап

Сроки примерные и плавающие.

| Блок | Что закрываем | Срок | Статус |
|---|---|---|---|
| 0 | Networking Basics, Packet Tracer, English for IT | окт 2026 | Готово |
| 1 | Networking Devices and Initial Configuration | окт 2026 | Готово |
| 2 | Network Addressing and Basic Troubleshooting, Проект 1 | ноя 2026 | Курс и Проект 1 готовы |
| 3 | CCNA 1: Introduction to Networks | ноя - дек 2026 | Следующий |
| 4 | CCNA 2: Switching, Routing and Wireless | янв - фев 2027 | |
| 5-6 | Пауза на экзамены и поступление | апр - авг 2027 | |
| 7 | CCNA 3: Enterprise Networking, Security and Automation + Проект 2 | июл - сен 2027 | |
| 8 | Linux + Проект 3 | сен - ноя 2027 | |
| 9 | Подготовка к CCNA, пробные экзамены, сам экзамен | дек 2027 - фев 2028 | |
| 10 | Основы ЦОД: железо, оптика, leaf-spine, BGP | мар - май 2028 | |
| 11 | Windows Server и Active Directory + Проект 4 | лето 2028 | |
| 12 | Дальше по очереди: FortiGate, Huawei VRP, SIEM и мониторинг, автоматизация, EVPN, облако и IaC, DevSecOps, MSSP MVP, затем AI и RDMA | без жёстких дат | |

### Принципы плана

1. Один блок до конца, потом следующий.
2. CCNA единственный приоритетный сертификат. Остальное подтверждаю проектами, а не бумагами.
3. BGP и VXLAN/EVPN не откладываю: база на этапе ЦОД, полноценная лаборатория позже.
4. Лаборатория на Proxmox, Containerlab, GNS3 и Packet Tracer.
5. Python только для автоматизации сетей и безопасности, без превращения в разработчика.
6. AI-инфраструктура и RDMA последними: сначала Ethernet, IP, BGP, leaf-spine.
7. Физика ЦОД обязательна: BMC/IPMI, RAID, PXE, SFP/QSFP, оптика, PDU, UPS, охлаждение, PUE.
8. Шаблонных проектов «для резюме» не плодю. Портфолио это 10-15 проектов из плана с README, схемой, IP-планом и журналом поломок.

## Сертификаты

- **Cisco CCNA (200-301):** главная цель, экзамен сдаю в блоке 9.
- **Huawei HCIA-Datacom:** второй вендор.
- **LFCS или RHCSA:** только если останется ресурс.

Пройдено в Cisco NetAcad: Networking Basics, Getting Started with Cisco Packet Tracer, English for IT 1 и четыре English for IT, Networking Devices and Initial Configuration, Network Addressing and Basic Troubleshooting.

## Итоговый стек

- **Сети:** TCP/IP, IPv4/IPv6, Ethernet, ARP/ICMP, VLAN/trunk, STP/RSTP, LACP/EtherChannel, OSPF, BGP (база), NAT, ACL, DHCP/DNS, VPN, Wi-Fi, QoS, VXLAN/EVPN (лаборатория в Containerlab/FRR).
- **Оборудование и безопасность сети:** Cisco IOS/IOS-XE, FortiGate/FortiOS, Huawei VRP, NGFW, IDS/IPS, DMZ, сегментация, Zero Trust.
- **Linux:** Ubuntu/Debian, RHEL-подобные, SSH, systemd, права, процессы, логи, Bash, nftables/ufw, Fail2ban, nginx.
- **Windows-инфраструктура:** Windows Server, Active Directory, LDAP, Group Policy, DNS, DHCP, Event Logs, PowerShell.
- **Кибербезопасность:** CIA, IAM, криптография (TLS, PKI, VPN), управление уязвимостями, threat modeling, incident response, hardening, аудит.
- **SIEM/SOC и мониторинг:** Wazuh, Splunk (знакомство), правила детектирования, FIM, syslog, Prometheus, Grafana, Alertmanager.
- **Автоматизация и разработка:** Git/GitHub, GitHub Actions, Bash, Ansible, Netmiko, Nornir, YAML, Python (для сетей и безопасности), REST API, FastAPI (минимум).
- **MSSP MVP:** Wazuh → Python/FastAPI → firewall → Ansible → подтверждение человеком.
- **Виртуализация и контейнеры:** Proxmox, Docker, Docker Compose, container security, CI/CD, сканирование образов.
- **Cloud и IaC:** AWS (VPC, EC2, S3, IAM, security groups), Terraform, hybrid cloud (концепции).
- **ЦОД:** серверное железо (BMC/IPMI, RAID, PXE), физический уровень (медь, оптика, SFP/QSFP, СКС), leaf-spine, питание и охлаждение (ИБП, PDU, генераторы, PUE), ITIL, NOC/SOC-процессы.
- **AI и HPC-сети (последними):** RDMA, InfiniBand, RoCEv2, PFC/ECN/DCB, lossless Ethernet, GPU cluster networking.

## Лаборатория

Kubuntu, Ryzen 5 5600, 32 ГБ RAM. Proxmox как вложенная ВМ в KVM, Containerlab с образами FRR, GNS3, Cisco Packet Tracer. Конфиги и скрипты в Git с первого дня.

## Структура репозитория

```
network-engineering-education/
├── README.md
├── project-1-office-network/
│   ├── README.md
│   ├── office-v1.pkt
│   └── topology.png
└── ...
```

Каждый следующий проект лежит в своей папке с таким же набором: README, схема, IP-план, журнал поломок.
