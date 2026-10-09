# ЛОКУС

Локальный офлайн ИИ-ассистент в браузере.

- WebLLM + WebGPU
- Лёгкая модель по умолчанию: **Qwen2.5-0.5B** (~280 МБ)
- Чаты, файлы, IndexedDB, стриминг

## Демо

После включения GitHub Pages:

**https://abrorismurzaev2-cpu.github.io/locus/**

Открывать в **Chrome / Edge 120+** (нужен WebGPU).

## Как включить Pages

1. Settings → Pages  
2. Source: **Deploy from a branch**  
3. Branch: `main` → folder `/ (root)` → Save  

Через 1–2 минуты сайт будет доступен.

## Локально

Открой `index.html` через локальный сервер (не `file://`):

```bash
npx serve .
```
