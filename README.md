# TP – Atelier Technologies WAN

Malik SAIED · RSI 3 · ISET de Nabeul · 2026/2027

Mes travaux pratiques de l'atelier WAN : comptes rendus (PDF et Word), projets GNS3 et vidéos réalisées avec ActivePresenter. Toutes les maquettes ont été montées sous GNS3 2.2.61 (routeurs Cisco 3725 sous Dynamips, hôtes VPCS).

## Travaux pratiques

| TP | Compte rendu | Projet GNS3 |
|---|---|---|
| Lab BGP | [PDF](Comptes-rendus/CR_Lab_BGP_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_Lab_BGP_Malik_SAIED.docx) | [TP_BGP](Projets-GNS3/TP_BGP_Malik_SAIED.gns3p) |
| Lab redistribution OSPF / RIPv2 / EIGRP | [PDF](Comptes-rendus/CR_Lab_Redistribution_OSPF_RIP_EIGRP_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_Lab_Redistribution_OSPF_RIP_EIGRP_Malik_SAIED.docx) | [TP_Redistribution_OSPF_EIGRP_RIP](Projets-GNS3/TP_Redistribution_OSPF_EIGRP_RIP_Malik_SAIED.gns3p) |
| Redistribution OSPF ↔ RIP (exemple du cours) | [PDF](Comptes-rendus/CR_Redistribution_cours_OSPF_RIP_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_Redistribution_cours_OSPF_RIP_Malik_SAIED.docx) | [TP_Redistribution_cours_OSPF_RIP](Projets-GNS3/TP_Redistribution_cours_OSPF_RIP_Malik_SAIED.gns3p) |
| TP 1 – MPLS, partie I | [PDF](Comptes-rendus/CR_TP1_MPLS_Partie1_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP1_MPLS_Partie1_Malik_SAIED.docx) | [TP1_MPLS](Projets-GNS3/TP1_MPLS_Malik_SAIED.gns3p) |
| TP 1 – MPLS, partie II | [PDF](Comptes-rendus/CR_TP1_MPLS_Partie2_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP1_MPLS_Partie2_Malik_SAIED.docx) | – |
| TP 2 – VPN MPLS | [PDF](Comptes-rendus/CR_TP2_VPN_MPLS_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP2_VPN_MPLS_Malik_SAIED.docx) | [TP2_MPLS_VPN](Projets-GNS3/TP2_MPLS_VPN_Malik_SAIED.gns3p) |
| TP 3 – DHCP et NAT | [PDF](Comptes-rendus/CR_TP3_DHCP_NAT_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP3_DHCP_NAT_Malik_SAIED.docx) | [TP3_DHCP_NAT](Projets-GNS3/TP3_DHCP_NAT_Malik_SAIED.gns3p) |
| TP 4 – VPN IPsec | [PDF](Comptes-rendus/CR_TP4_VPN_IPsec_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP4_VPN_IPsec_Malik_SAIED.docx) | [TP4_IPsec](Projets-GNS3/TP4_IPsec_Malik_SAIED.gns3p) |
| TP 4 – GRE over IPsec | [PDF](Comptes-rendus/CR_TP4_GRE_over_IPsec_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP4_GRE_over_IPsec_Malik_SAIED.docx) | [TP4_GRE_IPsec](Projets-GNS3/TP4_GRE_IPsec_Malik_SAIED.gns3p) |
| TP 6 – Frame Relay de base | [PDF](Comptes-rendus/CR_TP6_FrameRelay_base_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP6_FrameRelay_base_Malik_SAIED.docx) | [TP6_FR_base](Projets-GNS3/TP6_FR_base_Malik_SAIED.gns3p) |
| TP 6 – Frame Relay avancé (hub and spoke) | [PDF](Comptes-rendus/CR_TP6_FrameRelay_avance_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP6_FrameRelay_avance_Malik_SAIED.docx) | [TP6_FR_avance](Projets-GNS3/TP6_FR_avance_Malik_SAIED.gns3p) |
| TP ActivePresenter – vidéo de démonstration | [PDF](Comptes-rendus/CR_TP_ActivePresenter_Malik_SAIED.pdf) · [Word](Comptes-rendus/CR_TP_ActivePresenter_Malik_SAIED.docx) | – |

## Vidéos (ActivePresenter)

- [Redistribution OSPF / RIP – démonstration](Videos/TP_Redistribution_OSPF_RIP_Malik_SAIED.mp4)
- [Frame Relay avancé – topologie hub and spoke](Videos/TP6_FrameRelay_avance_Malik_SAIED.mp4)

## Organisation du dépôt

- `Comptes-rendus/` : un compte rendu par TP, en PDF et en Word.
- `Projets-GNS3/` : projets portables GNS3 (topologie et configurations).
- `Videos/` : capsules vidéo des démonstrations.

Pour ouvrir un projet : GNS3 → *File → Import portable project*. L'image Cisco IOS (c3725, IOS 12.4) n'est pas fournie et doit être ajoutée dans GNS3.
