<p align="center">
  <img src="img/image.png" width="120">
</p>

<h1 align="center">Cloud Image Vault</h1>

<p align="center">
Kumpulan link download Cloud Image resmi dari berbagai distro Linux — Ubuntu, Debian, AlmaLinux, Rocky Linux, dan lainnya — dalam satu tempat yang rapi.
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=2000&color=A855F7&center=true&vCenter=true&width=600&lines=Cloud+Image+Storage;Direct+Download+Links;Simple+%26+Easy+Access;Always+Learn%2C+Always+Update+%F0%9F%93%A6" />
</p>

<p align="center">

![Stack](https://img.shields.io/badge/Cloud_Image_Vault-Multi_OS_Image_List-A855F7?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Format](https://img.shields.io/badge/Format-qcow2_%2F_img-2496ED?style=flat-square&logo=qemu&logoColor=white)
![Status](https://img.shields.io/badge/Status-Actively_Updated-D97706?style=flat-square)

</p>

---

## ☁️ Overview

**Cloud Image Vault** adalah daftar link download resmi untuk Cloud Image dari berbagai sistem operasi, dikumpulkan manual biar gampang dicari sesuai kebutuhan — mau buat server production yang stabil, atau coba-coba versi terbaru.

Bukan mirror, bukan re-upload — semua link mengarah langsung ke sumber resmi masing-masing distro (Ubuntu, Debian, AlmaLinux, Rocky Linux, dst).

---

## ✨ Fitur

* Link download Cloud Image dari berbagai distro, dikelompokkan per OS
* Format `.img` / `.qcow2`, siap pakai buat cloud-init / KVM / Proxmox / OpenStack
* Tiap distro punya bagian (header) sendiri biar gak campur aduk
* Update setiap ada rilis baru atau build terbaru
* Format Markdown simpel, gampang dibaca di GitHub

---

## 🎯 Project Goals

* Jadi satu tempat referensi link download Cloud Image dari berbagai OS
* Memudahkan proses provisioning VM tanpa harus googling satu-satu
* Selalu update mengikuti rilis terbaru tiap distro
* Belajar terus, nambah distro baru kalau ada yang dibutuhkan

---

## 📦 Daftar Link Download

> Klik link untuk langsung download image. Semua link mengarah ke server resmi masing-masing distro.

### 🟠 Ubuntu

| Versi | Codename | Tipe | Link Download |
|---|---|---|---|
| 22.04 LTS | Jammy Jellyfish | Current (selalu terbaru) | [jammy-server-cloudimg-amd64.img](https://cloud-images.ubuntu.com/jammy/current/jammy-server-cloudimg-amd64.img) |
| 24.04 LTS | Noble Numbat | Current (selalu terbaru) | [noble-server-cloudimg-amd64.img](https://cloud-images.ubuntu.com/noble/current/noble-server-cloudimg-amd64.img) |
| 24.04 LTS | Noble Numbat | Build tanggal (snapshot) | [noble-server-cloudimg-amd64.img (20260225)](https://cloud-images.ubuntu.com/noble/20260225/noble-server-cloudimg-amd64.img) |

### 🔴 Debian

| Versi | Codename | Tipe | Link Download |
|---|---|---|---|
| 11 | Bullseye | Latest (genericcloud, qcow2) | [debian-11-genericcloud-amd64.qcow2](https://cloud.debian.org/images/cloud/bullseye/latest/debian-11-genericcloud-amd64.qcow2) |
| 12 | Bookworm | Latest (genericcloud, qcow2) | [debian-12-genericcloud-amd64.qcow2](https://cloud.debian.org/images/cloud/bookworm/latest/debian-12-genericcloud-amd64.qcow2) |
| 13 | Trixie | Latest (genericcloud, qcow2) | [debian-13-genericcloud-amd64.qcow2](https://cloud.debian.org/images/cloud/trixie/latest/debian-13-genericcloud-amd64.qcow2) |

### 🔵 AlmaLinux

| Versi | Tipe | Link Download |
|---|---|---|
| 8 | GenericCloud Latest (qcow2) | [AlmaLinux-8-GenericCloud-latest.x86_64.qcow2](https://repo.almalinux.org/almalinux/8/cloud/x86_64/images/AlmaLinux-8-GenericCloud-latest.x86_64.qcow2) |
| 9 | GenericCloud Latest (qcow2) | [AlmaLinux-9-GenericCloud-latest.x86_64.qcow2](https://repo.almalinux.org/almalinux/9/cloud/x86_64/images/AlmaLinux-9-GenericCloud-latest.x86_64.qcow2) |

### 🟢 Rocky Linux

| Versi | Tipe | Link Download |
|---|---|---|
| 9 | GenericCloud Base Latest (qcow2) | [Rocky-9-GenericCloud-Base.latest.x86_64.qcow2](https://dl.rockylinux.org/pub/rocky/9/images/x86_64/Rocky-9-GenericCloud-Base.latest.x86_64.qcow2) |

### ⚪ Lainnya

| OS | Versi | Link Download |
|---|---|---|
| _(tambahkan distro lain di sini, contoh: Fedora, openSUSE, Oracle Linux, dll)_ | — | _(letakkan link di sini)_ |

---

## 🏷️ Keterangan Tipe

* **Current / Latest** — Build terbaru dari versi tersebut, otomatis ke-update tiap ada patch tanpa link berubah. Paling direkomendasikan untuk dipakai sehari-hari.
* **Build tanggal (snapshot)** — Image dari tanggal build tertentu, link-nya fix dan gak berubah, cocok kalau butuh versi yang konsisten/reproducible.
* **LTS** — Versi *Long Term Support*, paling stabil, dapat dukungan keamanan jangka panjang. Cocok buat server production.
* **GenericCloud** — Image cloud universal yang bisa dipakai di hampir semua platform virtualisasi (KVM, Proxmox, OpenStack, dll) lewat cloud-init.

---

## 🧩 Cara Pakai

1. Pilih OS dan versi yang sesuai kebutuhan dari tabel di atas
2. Klik link untuk download file `.img` / `.qcow2`
3. Gunakan dengan `cloud-init`, import ke KVM/libvirt, Proxmox, atau platform cloud lain yang support format tersebut
4. (Opsional) Selalu cek file checksum (`SHA256SUMS` / `CHECKSUM`) di direktori yang sama sebelum dipakai, untuk memastikan integritas file

---

## 📜 License

This project is licensed under the MIT License.
See the LICENSE file for details.

---

<div align="center">
  <p>Made by Alfannite for you hehe 😊</p>

  <a href="https://github.com/alfannite">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://threads.net/@yeofanya">
    <img src="https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=threads&logoColor=white"/>
  </a>
  <a href="https://instagram.com/alfan.niteops">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="https://t.me/fannite_ops">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
  <a href="https://www.twitch.tv/fannitee">
    <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white"/>
  </a>
  <a href="https://discord.gg/mS4UXkQjW">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
  </a>
</div>