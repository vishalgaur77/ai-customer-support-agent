
# ai-customer-support-agent
🎙️ AI-Powered Customer Support Voice Agent using RAG architecture. Built with OpenAI GPT-4o, Qdrant Vector DB, and Firecrawl for real-time documentation crawling and voice-enabled responses.





## Features

- Knowledge Base Creation

  - Crawls documentation websites using Firecrawl
  - Stores and indexes content using Qdrant vector database
  - Generates embeddings for semantic search capabilities using FastEmbed
- **AI Agent Team**
  - **Documentation Processor**: Analyzes documentation content and generates clear, concise responses to user queries
  - **TTS Agent**: Converts text responses into natural-sounding speech with appropriate pacing and emphasis
  - **Voice Customization**: Supports multiple OpenAI TTS voices:
    - alloy, ash, ballad, coral, echo, fable, onyx, nova, sage, shimmer, verse

- **Interactive Interface**
  - Clean Streamlit UI with sidebar configuration
  - Real-time documentation search and response generation
  - Built-in audio player with download capability
  - Progress indicators for system initialization and query processing

## How to Run

1. **Setup Environment**
   ```bash
 # ai-customer-support-agent
 https://github.com/vishalgaur77
   
   # Install dependencies
   #
   pip install -r requirements.txt
   ```

3. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)
   - Get Qdrant API key and URL from [Qdrant Cloud](https://cloud.qdrant.io)
   - Get Firecrawl API key for documentation crawling

4. **Run the Application**
   ```bash
   streamlit run voice_ai.py
   
   ```

6. **Use the Interface**
   - Enter API credentials in the sidebar
   - Input the documentation URL you want to learn about
   - Select your preferred voice from the dropdown
   - Click "Initialize System" to process the documentation
   - Ask questions and receive both text and voice responses

## Features in Detail

- **Knowledge Base Creation**
  - Builds a searchable knowledge base from your documentation
  - Preserves document structure and metadata
  - Supports multiple page crawling (limited to 5 pages per default configuration)

- **Vector Search**
  - Uses FastEmbed for generating embeddings
  - Semantic search capabilities for finding relevant content
  - Efficient document retrieval using Qdrant

- **Voice Generation**
  - High-quality text-to-speech using OpenAI's TTS models
  - Multiple voice options for customization
  - Natural speech patterns with proper pacing and emphasis 
 ye mene readme me daala hai
