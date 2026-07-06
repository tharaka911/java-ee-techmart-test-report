# TechMart Test Reports

Simple static project for publishing the generated JMeter reports to Vercel.

## Local preview

```bash
npm run dev
```

Open `http://localhost:3000`.

## Deploy to Vercel

1. Create a new Vercel project.
2. Select this folder as the project root: `/Users/tharaka/Downloads/techmart-report`.
3. Keep the framework preset as `Other`.
4. Leave build command and output directory empty.
5. Deploy.

The home page lists all reports. Each card links to the original generated JMeter dashboard and its `statistics.json`.
