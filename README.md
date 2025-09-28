# Kotlin Coroutines Notebooks

A collection of interactive Kotlin notebooks demonstrating coroutines concepts and patterns using JetBrains Kotlin Notebook.

## 📋 Overview

This repository contains hands-on examples and tutorials for learning Kotlin coroutines through interactive notebooks. Each notebook focuses on specific coroutines concepts with practical, runnable code examples.

## 📚 Notebooks

### Coroutines/
- **[basics.ipynb](Coroutines/basics.ipynb)** - Fundamental coroutine patterns including launch, async/await, structured concurrency, cancellation, and Flow basics
- **[101_kotlin_coroutines.ipynb](Coroutines/101_kotlin_coroutines.ipynb)** - Comprehensive introduction to Kotlin coroutines
- **[cancellation_basics.ipynb](Coroutines/cancellation_basics.ipynb)** - Deep dive into coroutine cancellation mechanisms
- **[exceptions.ipynb](Coroutines/exceptions.ipynb)** - Exception handling patterns in coroutines
- **[flows.ipynb](Coroutines/flows.ipynb)** - Advanced Flow operations and patterns
- **[supervisor_job_and_scope.ipynb](Coroutines/supervisor_job_and_scope.ipynb)** - SupervisorJob and scope management

## 🚀 Key Topics Covered

- **Basic Coroutines**: `launch`, `runBlocking`, `async`/`await`
- **Structured Concurrency**: `coroutineScope`, parent-child relationships
- **Cancellation**: Explicit cancellation, timeouts, cleanup
- **Context Switching**: `withContext`, `Dispatchers`
- **Flow**: Cold streams, operators, collection
- **Exception Handling**: Error propagation, structured exception handling
- **Supervision**: `SupervisorJob`, fault tolerance

## 🛠️ Requirements

- **JetBrains IntelliJ IDEA** or **JetBrains DataSpell** with Kotlin Notebook support
- **Kotlin** 1.8+
- **kotlinx-coroutines-core** 1.8.1+ (automatically managed via `@file:DependsOn`)

## 🏃 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/smithjustinn84-netizen/notebooks.git
   cd notebooks
   ```

2. **Open in JetBrains IDE**:
   - Open the project in IntelliJ IDEA or DataSpell
   - Navigate to the `Coroutines/` directory
   - Open any `.ipynb` file to start learning

3. **Run the notebooks**:
   - Execute cells individually to see coroutines in action
   - Modify examples to experiment with different patterns
   - Dependencies are automatically resolved via `@file:DependsOn`

## 📖 Learning Path

For beginners, we recommend following this order:

1. **[basics.ipynb](Coroutines/basics.ipynb)** - Start here for fundamental concepts
2. **[101_kotlin_coroutines.ipynb](Coroutines/101_kotlin_coroutines.ipynb)** - Comprehensive overview
3. **[cancellation_basics.ipynb](Coroutines/cancellation_basics.ipynb)** - Understanding cancellation
4. **[exceptions.ipynb](Coroutines/exceptions.ipynb)** - Error handling patterns
5. **[flows.ipynb](Coroutines/flows.ipynb)** - Reactive streams with Flow
6. **[supervisor_job_and_scope.ipynb](Coroutines/supervisor_job_and_scope.ipynb)** - Advanced scope management

## 🔧 Interactive Features

Each notebook includes:
- ✅ **Runnable code examples** with real output
- ✅ **Detailed explanations** of coroutine concepts
- ✅ **Timing measurements** to understand concurrency benefits
- ✅ **Exception handling** demonstrations
- ✅ **Best practices** and common patterns

## 🤝 Contributing

Feel free to:
- Add new notebook examples
- Improve existing explanations
- Fix any issues you encounter
- Suggest new coroutines topics to cover

## 📝 Notes

- All notebooks use `runBlocking` for demo purposes in a notebook environment
- In production apps, prefer structured concurrency with proper scope management
- Examples include timing measurements to demonstrate concurrent execution
- Dependencies are managed automatically via notebook annotations

## 🔗 Resources

- [Kotlin Coroutines Guide](https://kotlinlang.org/docs/coroutines-guide.html)
- [kotlinx.coroutines Documentation](https://kotlinlang.org/api/kotlinx.coroutines/)
- [JetBrains Kotlin Notebook Documentation](https://kotlinlang.org/docs/kotlin-notebook-overview.html)

---

**Happy Learning!** 🎉 Explore the world of asynchronous programming with Kotlin coroutines through these interactive examples.