# Paint Automation with AI Integration

## Project Overview
This project, developed as part of the EAG Course's 4th Week Assignment, demonstrates the integration of AI-driven automation with Microsoft Paint. It creates an interactive presentation system that explains mathematical concepts through visual representation.

## Core Features
- **AI-Driven Content Generation**: Utilizes Google's Gemini AI model for generating mathematical explanations
- **Automated Paint Control**: Programmatically controls MS Paint for drawing and text placement
- **Real-time Visualization**: Creates visual representations of mathematical concepts
- **Error Handling**: Robust error management system for reliable operation

## Technical Architecture

### 1. MCP (Model-Control-Protocol) Server
- **Communication Handler**: Manages bidirectional communication between AI model and Paint
- **Tool Management**: Coordinates execution of various automation tools
- **State Management**: Maintains application state and handles transitions
- **Error Control**: Implements comprehensive error handling and recovery

### 2. Automation Tools
#### Paint Control Functions
- `draw_rectangle(x1, y1, x2, y2)`: Creates rectangles with specified coordinates
- `add_text_in_paint(text, x, y)`: Places text at given locations
- `open_paint()`: Initializes and configures MS Paint window

#### Mathematical Operations
- **Basic Operations**: Addition, subtraction, multiplication, division
- **Advanced Functions**: 
  - Power calculations
  - Square and cube roots
  - Factorial computation
  - Logarithmic operations
- **Trigonometric Functions**: Sine, cosine, tangent
- **Special Functions**: 
  - Fibonacci sequence generation
  - Exponential sum calculations

## Implementation Example
The project demonstrates its capabilities through an example that:
1. Explains the calculation of e^5.342
2. Creates visual boxes for each explanation step
3. Adds corresponding text within the boxes
4. Maintains visual clarity and proper spacing

## Technical Requirements
- Python 3.x
- Google Gemini AI API access
- Windows OS (for MS Paint integration)
- Required Python packages:
  - pywinauto
  - win32gui
  - FastMCP
  - Google Generative AI