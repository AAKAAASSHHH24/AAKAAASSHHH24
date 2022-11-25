- 👋 Hi, I’m Akash Kr Rakshit
- 👀 I’m interested in Data Science, Machine Learning and Football related Data Analytics.
- 🌱 I’m currently learning Deep learning Projects in Computer Vision.
- 💞️ I’m looking to collaborate on projects of my interests
- 📫 How to reach me: akashrksht@gmail.com

<!---
AAKAAASSHHH24/AAKAAASSHHH24 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<img 
   src="https://github-readme-stats.vercel.app/api?username=AAKAAASSHHH24&show_icons=true&theme=tokyonight" 
/>


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AAKAAASSHHH24&layout=compact)](https://github.com/AAKAAASSHHH24/github-readme-stats)


# file .github/workflows/activity.yml
name: Update README

            on:
              schedule:
                - cron: '*/30 * * * *'
              workflow_dispatch:
            
            jobs:
              build:
                runs-on: ubuntu-latest
                name: Update this repo's README with recent activity
            
                steps:
                  - uses: actions/checkout@v2
                  - uses: jamesgeorge007/github-activity-readme@master
                    env:
                      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

