## Setup

1. Clone with submodules:
   \`\`\`bash
   git clone --recurse-submodules https://github.com/bigbrownking/ai_investigator_infrastructure
   cd digital-infrastructure
   \`\`\`

2. If already cloned, initialize submodules:
   \`\`\`bash
   git submodule update --init --recursive
   \`\`\`

3. Start services:
   \`\`\`bash
   docker-compose up -d
   \`\`\`

## Update Submodules

\`\`\`bash
git submodule update --remote
\`\`\`
