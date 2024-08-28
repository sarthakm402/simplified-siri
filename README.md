
# Simplified Siri

This Flask application utilizes Google's Generative AI to generate and stream text responses based on user prompts. It features real-time streaming of content and includes specific configurations to handle mental health-related prompts.


## Overview

- **Generative Model Integration**: Leverages Google Generative AI for text generation.

- **Real-Time Streaming**: Streams text responses directly to the client in real time.


- **Special Handling for Mental Health Prompts**: Custom behavior for prompts containing "hey siri" related to mental health.

## Prerequisites

- Python 3.6 or later
- Google Generative AI API key

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/sarthakm402/simplified-siri.git
  
## Usage/Examples

- Access the Web Interface

Navigate to http://127.0.0.1:5000/ in your browser.

Send a POST Request

Use a tool like curl or Postman to send a POST request with JSON data. 

The application will stream the generated response back to you.



##  Configuration Details

- Generation Parameters:

    - temperature: 0.9 (controls the randomness of the    generated        text)
    - top_p: 1 (cumulative probability for token selection)

    - top_k: 1 (number of highest probability tokens to consider)
 
    - max_output_tokens: 4096 (maximum tokens in the output)

- Safety Settings:

    - Harassment: Block medium and above

    -  Hate Speech: Block medium and above

    - Sexually Explicit: Block medium and above
    
    - Dangerous Content: Block medium and above
## Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

- Fork the repository.

- Create a new branch for your changes.

- Commit your changes.

- Push to your fork.
 
- Create a pull request.



