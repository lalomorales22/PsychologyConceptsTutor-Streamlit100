# Psychology Concepts Tutor

Psychology Concepts Tutor is an interactive Streamlit application designed to help students learn and understand psychological theories and practices. Leveraging AI technology, it provides explanations, generates quizzes, and offers various learning modes across different branches of psychology.

## Features

- Comprehensive coverage of major psychology branches
- Multiple learning modes to suit different study preferences
- AI-powered explanations and quiz generation
- Customizable difficulty levels
- Interactive chat interface for asking questions
- Quiz mode with multiple-choice questions
- Conversation saving and loading functionality
- Token usage tracking for AI interactions
- Dark/Light theme options

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/lalomorales22/PsychologyConceptsTutor-Streamlit100.git
   cd psychology-concepts-tutor
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and navigate to `http://localhost:8501`

3. Configure your learning session:
   - Enter your name
   - Select a psychology branch
   - Choose a learning mode
   - Set the difficulty level

4. Interact with the AI tutor:
   - Ask questions about psychology concepts
   - Request explanations of theories and practices
   - Take quizzes to test your knowledge

5. Explore different learning modes:
   - Concept Explanation
   - Case Studies
   - Theory Comparison
   - Research Methodology
   - Ethical Considerations
   - Historical Context
   - Practical Applications
   - Key Figures
   - Quiz Mode

## Customization

- Modify the `PSYCHOLOGY_BRANCHES` and `LEARNING_MODES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to fine-tune the AI's behavior

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the psychology students and educators who provided feedback during development
- Special thanks to the open-source community for the libraries and frameworks used in this project

## Support

If you encounter any issues or have questions, please file an issue on the GitHub repository.

Happy learning, future psychologists!
