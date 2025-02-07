# Community & AI-Based Podcast

Welcome to the Pull Request Podcast! This community-driven initiative transforms text contributions into technical podcast episodes. Every midnight, any new or updated text file containing key points for a 10-minute episode is processed and published as a podcast available on [Spotify](https://open.spotify.com/show/4GioQMJoZ9pEyY4SnoI0oA) and [Apple Podcasts](https://podcasts.apple.com/us/podcast/pull-request/id1795035005).

## How It Works

- **Collaborative Contributions:**  
  Anyone can contribute by uploading or editing text files in the episodes folder. While the file can be empty, it's best if it contains concise key points and highlights for a 10-minute episode.

- **Dynamic Updates:**  
  If you've listened to an episode and feel that something is missing, simply update the corresponding text file. Your changes will be integrated into future episodes to keep the content fresh and accurate.

- **Credits:**  
  Feel free to add your name to your submission. Contributors who include their name will be credited in the podcast episode.

- **Content Guidelines:**
  - Make sure the filename is properly capitalized (i.e MySQL.txt instead of mysql.txt)
  - Focus on technical topics
  - Contributions must be in English

## Technologies

- **Thinking Model:** o1
- **Text-to-Speech:** OpenAI

## How to Contribute

1. **Fork the Repository**

2. **Clone Your Fork:**

   ```bash
   git clone https://github.com/yourusername/pull-request-podcast.git
   ```

3. **Create a New Branch:**

   ```bash
   git checkout -b add-episode-content
   ```

4. **Add or Update a Text File:**  
   In the `episodes/` directory, add a new text file (example: `MySQL.txt`) following the guidelines for a 10-minute technical episode. If updating an existing file, include your improvements and optionally add your name in the credits section.

5. **Commit Your Changes:**

   ```bash
   git add .
   git commit -m "Added/Updated episode content for [specific date/topic]"
   ```

6. **Push Your Changes:**

   ```bash
   git push origin add-episode-content
   ```

7. **Create a Pull Request:**  
   Once your branch is pushed, open a pull request. The maintainers will review your contribution before merging it. Once merged, the updated content will be processed automatically at midnight into a new podcast episode.

Thanks for listening! ❤️

Michael Lugassy

Follow me on [LinkedIn](https://www.linkedin.com/in/mluggy/) & [X](https://x.com/mluggy).
