# Python A2A Examples

This directory contains practical examples demonstrating how to use the Python A2A library. Each example is designed to showcase different aspects of the A2A protocol and help you quickly implement agent-to-agent communication in your projects.

## 🚀 Quick Start

If you're new to Python A2A, start with these examples:

1. [**Hello A2A**](getting_started/hello_a2a.py) - Create your first A2A messages in just a few lines of code
2. [**Simple Client**](getting_started/simple_client.py) - Connect to any A2A-compatible agent
3. [**Simple Server**](getting_started/simple_server.py) - Create your own basic A2A server
4. [**Basic Streaming**](streaming/01_basic_streaming.py) - Implement real-time streaming responses

## 🗺️ Example Categories

### Getting Started (Beginner Level)

These examples provide a gentle introduction to A2A concepts:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [Hello A2A](getting_started/hello_a2a.py) | The simplest possible example | Creating basic messages |
| [Simple Client](getting_started/simple_client.py) | Connect to any A2A agent | Sending requests and handling responses |
| [Simple Server](getting_started/simple_server.py) | Build a basic A2A server | Creating your first agent |
| [Function Calling](getting_started/function_calling.py) | Add function calling capabilities | Executing functions through A2A |

### Streaming (Real-time Responses)

These examples demonstrate how to implement streaming responses:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [Basic Streaming](streaming/01_basic_streaming.py) | Simple streaming implementation | Creating and consuming streams |
| [Advanced Streaming](streaming/02_advanced_streaming.py) | Advanced streaming techniques | Metrics tracking and chunking strategies |
| [LLM Integration](streaming/03_streaming_llm_integration.py) | Stream from LLM providers | Connecting provider APIs with A2A streaming |
| [Task-Based Streaming](streaming/04_task_based_streaming.py) | Structured streaming with tasks | Progress tracking and artifacts |
| [UI Integration](streaming/05_streaming_ui_integration.py) | Stream to user interfaces | CLI and web-based streaming visualization |
| [Distributed Streaming](streaming/06_distributed_streaming.py) | Multi-node streaming | Load balancing and fault tolerance |

### Building Blocks (Core Concepts)

These examples demonstrate fundamental A2A components:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [Agent Discovery](building_blocks/agent_discovery.py) | Create and understand agent cards | Agent capability discovery |
| [Messages and Conversations](building_blocks/messages_and_conversations.py) | Work with message objects | Building complex conversations |
| [Tasks](building_blocks/tasks.py) | Understand the A2A task model | Managing stateful agent interactions |
| [Agent Skills](building_blocks/agent_skills.py) | Create agents with defined skills | Using decorators for clean agent definitions |

### AI-Powered Agents (Integration with LLMs)

Connect A2A to various AI services:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [OpenAI Agent](ai_powered_agents/openai_agent.py) | Create GPT-powered agents | Connecting to OpenAI |
| [Anthropic Agent](ai_powered_agents/anthropic_agent.py) | Create Claude-powered agents | Connecting to Anthropic |
| [Bedrock Agent](ai_powered_agents/bedrock_agent.py) | Use AWS Bedrock models | Connecting to AWS Bedrock |
| [LLM Client](ai_powered_agents/llm_client.py) | Direct connection to LLMs | Working with various LLM providers |

### Agent Network Examples

Build and manage networks of cooperating agents:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [Basic Workflow](agent_network/basic_workflow.py) | Create condition-based workflows | Building and executing agent workflows |
| [Parallel Workflow](agent_network/parallel_workflow.py) | Execute tasks concurrently | Parallel execution for better performance |
| [Agents Workflow](agent_network/agents_workflow.py) | Orchestrate LLM-powered agents | Intelligent routing between AI models |
| [Smart Routing](agent_network/smart_routing.py) | Route queries to specialized agents | AI-driven query analysis and routing |
| [Agent Discovery](agent_network/agent_discovery.py) | Automatically discover available agents | Dynamic agent network management |

### Model Context Protocol (MCP) Tools

Add external tool capabilities to your agents:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [MCP Tools](mcp/mcp_tools.py) | Create MCP-compatible tools | Defining tools for AI agents |
| [MCP Agent](mcp/mcp_agent.py) | Build agents that use MCP tools | Connecting agents to tools |
| [OpenAI MCP Agent](mcp/openai_mcp_agent.py) | OpenAI agent with MCP tools | Combining OpenAI with external tools |

### Complete Applications

End-to-end examples for real-world use cases:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [Weather Assistant](applications/weather_assistant.py) | Weather information agent | Building a domain-specific agent |
| [OpenAI Travel Planner](applications/openai_travel_planner.py) | AI-powered travel planner | Combining multiple capabilities |

### Developer Tools

Tools to enhance your development workflow:

| Example | Description | Key Learning |
|---------|-------------|--------------|
| [CLI Tools](developer_tools/cli_tools.py) | Command-line tools | Working with A2A via terminal |
| [Interactive Docs](developer_tools/interactive_docs.py) | Generate API documentation | Creating documentation for your agents |
| [Testing Agents](developer_tools/testing_agents.py) | Test A2A agents | Writing tests for agents |

## 🔍 Finding the Right Example for Your Needs

### Based on Your Role

- **AI/ML Engineers**: Start with the AI-powered agent examples to see how to integrate with LLMs
- **Backend Developers**: Begin with the building blocks examples to understand the core protocol
- **Frontend Developers**: The simple client example shows how to connect to A2A agents
- **DevOps Engineers**: Check the CLI tools example for automation capabilities

### Based on Your Goals

- **I want to call an existing AI agent**: [Simple Client](getting_started/simple_client.py)
- **I need to build my own agent**: [Simple Server](getting_started/simple_server.py) or [Agent Skills](building_blocks/agent_skills.py)
- **I want to use OpenAI with A2A**: [OpenAI Agent](ai_powered_agents/openai_agent.py)
- **I need to implement streaming responses**: [Basic Streaming](streaming/01_basic_streaming.py)
- **I want to integrate streaming with LLMs**: [LLM Integration](streaming/03_streaming_llm_integration.py)
- **I need to build a streaming UI**: [UI Integration](streaming/05_streaming_ui_integration.py)
- **I need to route queries to specialized agents**: [Smart Routing](agent_network/smart_routing.py)
- **I want to execute tasks concurrently**: [Parallel Workflow](agent_network/parallel_workflow.py)
- **I need to create agent workflows**: [Basic Workflow](agent_network/basic_workflow.py)
- **I want to discover agents automatically**: [Agent Discovery](agent_network/agent_discovery.py)
- **I need to add external tools to my agent**: [MCP Tools](mcp/mcp_tools.py)
- **I want to build a complete application**: [Weather Assistant](applications/weather_assistant.py)

## 🛠️ Running the Examples

Most examples can be run with:

```bash
python example_name.py
```

Some examples require API keys or additional setup. Check the comments at the top of each file for specific requirements and instructions.

### Common Requirements

```bash
# For basic examples
pip install python-a2a

# For server examples
pip install "python-a2a[server]"

# For LLM integration
pip install "python-a2a[openai]" "python-a2a[anthropic]" "python-a2a[bedrock]"

# For MCP (tool) support
pip install "python-a2a[mcp]"

# For everything
pip install "python-a2a[all]"
```

## 📚 Learning Path

For a structured learning experience, we recommend following this sequence:

1. **Start with the basics**: Run through the Getting Started examples
2. **Understand core concepts**: Explore the Building Blocks examples
3. **Add AI capabilities**: Try the AI-Powered Agents examples
4. **Implement streaming**: Explore the Streaming examples for real-time responses
5. **Learn agent networking**: Experiment with the Agent Network examples
6. **Extend with tools**: Experiment with the MCP examples
7. **Build complete applications**: Study the Applications examples
8. **Improve your workflow**: Use the Developer Tools examples

## 🤝 Contributing

Have an idea for a new example? We welcome contributions! Please check the [CONTRIBUTING.md](../CONTRIBUTING.md) file for guidelines.

## 🧪 Validating Examples

The python-a2a project includes a comprehensive validation system to ensure all examples work correctly. This is especially valuable before releases or after making significant changes.

### Running Validation

```bash
# Validate all examples
python validate_all_examples.py

# Validate a specific category
python validate_all_examples.py --category streaming

# Skip slow examples for faster validation
python validate_all_examples.py --skip-slow

# Run examples concurrently for faster validation (be careful with server examples)
python validate_all_examples.py --concurrent 3

# Show detailed output for debugging
python validate_all_examples.py --verbose
```

### Validation Output

The validation script provides detailed output including:

- Overall success/failure statistics
- Category-by-category results
- Detailed error messages for failing examples
- Skipped examples (due to missing dependencies or API keys)

Example output:
```
===============================================================================
VALIDATION SUMMARY
===============================================================================

Overall Results:
Total examples: 42
Passed: 39
Failed: 2
Skipped: 1

Category Results:
getting_started: [All 4 passed]
building_blocks: [All 4 passed]
streaming: [6/7 passed, 1 failed]
ai_powered_agents: [3/4 passed, 1 failed]
applications: [All 2 passed]
agent_network: [All 3 passed]
workflows: [All 3 passed]
mcp: [All 3 passed]
langchain: [All 4 passed]
developer_tools: [All 3 passed]

Failed Examples:
• streaming/06_distributed_streaming.py: Example timed out after 30 seconds
• ai_powered_agents/openai_agent.py: Missing API key environment variable: OPENAI_API_KEY

Skipped Examples:
• applications/openai_travel_planner.py: Skipped (missing API key: OPENAI_API_KEY)

--------------------------------------------------------------------------------
✗ Validation found 2 failing examples.
--------------------------------------------------------------------------------
```

### Using Validation in Development

- Run validation before submitting pull requests
- Run validation after making significant changes
- Include validation in CI/CD pipelines
- Use `--category` to focus on specific areas you're working on

## 📄 License

All examples are released under the MIT License. See the [LICENSE](../LICENSE) file for details.