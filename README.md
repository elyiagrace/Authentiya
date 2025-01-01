# AuthentiHash: View DevPost with video Demo @ https://devpost.com/software/ellia-morse

## Inspiration
With the rise of AI-generated content in academic and commercial settings, consumers increasingly want to know if the content they encounter is authentic. Creators also need to protect their work from accusations of being AI-generated, especially since AI-created work cannot be protected by copyright law. Additionally, AI-generated text can lead to issues like misleading information, bias, and poor quality control when authors copy and paste content from language models. There must be a way to verify whether content is genuinely human-created.

## What It Does
This project introduces a text editor that tracks users' keystrokes as they type. The keystroke logger detects actions such as "backspace," "delete," "enter," and "space," and logs when content is copied and pasted into the text box. When the user clicks "save," the keystrokes, along with a date-time stamp, are hashed to create a unique fingerprint for the document.

## Challenges We Ran Into
We deployed a blockchain-agnostic contract written in Solidity to the Sepolia test network. The user can log in to their MetaMask wallet upon loading the page. However, we did not integrate the wallet address to log hashes on the blockchain. This integration would be a crucial next step for the project.

## Accomplishments We're Proud Of
This project was filled with firsts, including learning how blockchain technology works and using tools like Hardhat, Remix, Truffle, and Ganache for blockchain development. Additionally, we implemented the cryptographic function SHA-256 to hash user input.

## Future Roadmap
We envision multiple applications for this tool, such as integration with academic platforms like TurnItIn or Canvas to provide proof of process for graders. To achieve broader adoption, the tool could be developed into a browser plugin compatible with popular text editors like Google Docs and Microsoft Word. Potential future features include:

- Mapping identity to writing through biometric authentication (e.g., face ID, fingerprint) or multi-factor authentication.
- Downloading documents with metadata for authorship verification.
- Storing documents in a decentralized way using the InterPlanetary File System (IPFS).
- Enabling a UI to retrieve version history and restore earlier document versions.
- Sharing proof of authenticity in an accessible format.
- Integrating plagiarism detection tools.
- Issuing alerts for copied/pasted text when sharing documents.
- Automatically clearing alerts for properly cited content.
- Supporting multiple authors and delineating individual contributions.

## Research and Further Reading
- Appel, Gil, et al. “[Generative AI Has an Intellectual Property Problem](https://hbr.org/2023/04/generative-ai-has-an-intellectual-property-problem).” Harvard Business Review, 11 Apr. 2023.
- “[Author’s Rights - Author’s Rights and Copyright](https://guides.library.illinois.edu/AuthorsRights).” University of Illinois at Urbana-Champaign.
- Brittain, Blake. “[AI-Generated Art Cannot Receive Copyrights, US Court Says](https://www.reuters.com/legal/ai-generated-art-cannot-receive-copyrights-us-court-says-2023-08-21).” Reuters, 21 Aug. 2023.
- Hyken, Shep. “[Half of People Who Encounter Artificial Intelligence Don’t Even Realize It](https://www.forbes.com/sites/forbesbusinessdevelopmentcouncil/2017/06/12/half-of-people-who-encounter-artificial-intelligence-dont-even-realize-it/).” Forbes, 12 June 2017.


“Libguides: Author’s Rights and Copyright: Author’s Rights.” Author’s Rights - Author’s Rights and Copyright - LibGuides at University of Illinois at Urbana-Champaign, guides.library.illinois.edu/AuthorsRights

Brittain, Blake. “AI-Generated Art Cannot Receive Copyrights, US Court Says | Reuters.” Reuters, 21 Aug. 2023. https://www.reuters.com/legal/ai-generated-art-cannot-receive-copyrights-us-court-says-2023-08-21/

Hyken, Shep. “Half of People Who Encounter Artificial Intelligence Don’t Even Realize It.” Forbes, Forbes Magazine, 12 June 2017, www.forbes.com/sites/
