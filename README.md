# AI Fintech Asset Management MVP Proposal

Static Vercel deploy package for the AI fintech asset management MVP proposal.

## Routes

- `/` renders the clickable UX HTML preview.
- `/proposal.pdf` downloads the proposal PDF.
- `/proposal` rewrites to `/proposal.pdf`.
- `/portfolio.pdf` opens the BigShift portfolio PDF inline.
- `/portfolio` rewrites to `/portfolio.pdf`.

## Vercel Setup

1. Vercel dashboard에서 Add New... > Project를 선택합니다.
2. GitHub repository `bigshift-projects/ai-fintech-asset-management-mvp`를 선택합니다.
3. Framework Preset은 Other 또는 자동 감지값을 둡니다.
4. Root Directory는 repository root로 둡니다.
5. Build Command는 비웁니다.
6. Output Directory도 비웁니다.
7. Deploy를 누릅니다.

Codex는 GitHub 업로드까지만 수행합니다. Vercel import와 실제 deployment 실행은 사용자가 직접 진행해야 합니다.

After deployment, use:

- `https://<vercel-project>.vercel.app/` for the UX preview
- `https://<vercel-project>.vercel.app/proposal` for the PDF download
- `https://<vercel-project>.vercel.app/portfolio` for the BigShift portfolio PDF

