# Text-to-Image Prompt Alignment — Survey & Analysis

A course project (AI Capstone) from Ho Chi Minh City University of Technology (HCMUT),
analyzing state-of-the-art methods for improving semantic alignment between text prompts 
and generated images in diffusion-based Text-to-Image models.

## Overview

Despite impressive advances, modern T2I models like Stable Diffusion still struggle with:
- **Concept Ignorance** — missing entities from the input prompt
- **Concept Mismapping** — incorrect attribute-to-object assignment

This report surveys three methods addressing these issues from different angles.

## Methods Analyzed

| Method | Core Idea | Target Problem |
|---|---|---|
| **AlignProp** | Reward backpropagation through denoising chain | General prompt alignment |
| **RealignDiff** | Coarse-to-fine semantic re-alignment | Missing objects & local misalignment |
| **CoMat** | Cross-attention concept & attribute control | Concept ignorance & mismapping |

## Proposed Direction

A sequential fine-tuning pipeline combining all three:
1. **Stage 1 — AlignProp**: Global prompt alignment via reward backpropagation
2. **Stage 2 — RealignDiff**: Fix missing objects and relational errors
3. **Stage 3 — CoMat**: Fine-grained attribute-to-region mapping correction

## Report

Full report (Vietnamese): [đồ_án_trí_tuệ_nhân_tạo.pdf](./đồ_án_trí_tuệ_nhân_tạo.pdf)

## Course Info

- **Course**: Đồ Án Tổng Hợp - Hướng Trí Tuệ Nhân Tạo (đạt 10/10 điểm)
- **Supervisor**: Ths. Vương Bá Thịnh  
- **Student**: Nguyễn Cảnh Nguyên — MSSV: 2312357  
- **University**: HCMUT — December 2025
