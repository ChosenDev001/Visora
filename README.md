# MotionSound

## Run locally on Windows
1. Extract this ZIP.
2. Open the extracted `motionsound-ai-fixed` folder in VS Code.
3. Open Terminal → New Terminal and make sure it is in the folder containing `package.json`.
4. Run `npm install`, wait for it to finish, then run `npm run dev`.
5. Open the exact `Local` address Vite prints, usually `http://localhost:5173/`.
6. Click **Start camera** and allow camera permission.

Keep the terminal open while testing.

## Deploy to GitHub Pages
Upload `index.html`, `package.json`, and `README.md` to the root of a GitHub repository. In Settings → Pages, choose **Deploy from a branch**, select `main` and `/(root)`, then save. Wait for the HTTPS website link. Every visitor must grant camera permission.

The detection library and model files load from public internet CDNs, so internet access is required. The camera feed is processed in the browser. This demo detects face/hand/body landmarks and a basic raised-hand cue; it does not identify people or interpret every possible action.
