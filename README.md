# Yuvraj Vijay Verma — Portfolio

Clean, static portfolio ready for zero-config deployment on Vercel.

## Deployment Options

### Option 1: Deploy with Vercel CLI (Fastest)

1. Open your terminal in this directory:
   ```bash
   cd /home/yuvraj/yuvraj_portfolio
   ```

2. Run Vercel deploy:
   ```bash
   npx vercel
   ```
   Follow the prompts to link your Vercel account and deploy.

3. For production deployment:
   ```bash
   npx vercel --prod
   ```

---

### Option 2: Deploy via GitHub + Vercel Dashboard

1. Initialize git and commit:
   ```bash
   cd /home/yuvraj/yuvraj_portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. Push to your GitHub account:
   ```bash
   git remote add origin https://github.com/shivamverma99399-bit/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```

3. Go to [vercel.com](https://vercel.com) -> **Add New Project** -> Import your GitHub repository.
4. Leave settings as default (Framework Preset: **Other**) and click **Deploy**.
