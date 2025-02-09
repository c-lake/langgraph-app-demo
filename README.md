- https://langchain-ai.github.io/langgraph/tutorials/langgraph-platform/local-server/


Takeaways:
- Pass configs into tools using `runnable_config`. Use type annotation `InjectedToolArg`
- Use env variables to configure tools whenever relevant to different deployments
- Consider runnable configs seriously as this is by design of LangGraph
- Any graph can be used with LangGraph Studio
- Next steps: still to play with deterministic tool nodes