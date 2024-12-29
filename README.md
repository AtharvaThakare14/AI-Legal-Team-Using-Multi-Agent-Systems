#  AI Legal Agent Team

- **Legal Researcher**: Equipped with DuckDuckGo search tool to find and cite relevant legal cases and precedents. Provides detailed research summaries with sources and references specific sections from uploaded documents.
  
  - **Contract Analyst**: Specializes in thorough contract review, identifying key terms, obligations, and potential issues. References specific clauses from documents for detailed analysis.
  
  - **Legal Strategist**: Focuses on developing comprehensive legal strategies, providing actionable recommendations while considering both risks and opportunities.
  
  - **Team Lead**: Coordinates analysis between team members, ensures comprehensive responses, properly sourced recommendations, and references to specific document parts. Acts as an Agent Team coordinator for all three agents.

## How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
   git clone https://github.com/AtharvaThakare14/AI-Legal-Team-Using-Multi-Agent-Systems.git
   
   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)
   - Get Qdrant API key and URL from [Qdrant Cloud](https://cloud.qdrant.io)

3. **Run the Application**
   ```bash
   streamlit run legal_agent_team.py
   ```
4. **Use the Interface**
   - Enter API credentials
   - Upload a legal document (PDF)
   - Select analysis type
   - Add custom queries if needed
   - View analysis results
