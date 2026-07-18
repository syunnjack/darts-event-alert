# Darts Event Alert

ダーツ台・大会通知

## Repository

Recommended repository name: `darts-event-alert`

## Domain candidates

Confirmed domain: `dartsevent.jp`

Other candidates:

- `dartsevent.jp`
- `dartsalert.jp`
- `dartboard.jp`
- `dartnavi.jp`

## Concept

DARTSLIVE設置店、大会、空き台、キャンペーンを通知し、店舗送客と用品アフィリエイトにつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 店舗送客
- 用品 affiliate
- 大会掲載
- バー求人
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
