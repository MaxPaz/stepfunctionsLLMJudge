Using the following prompt as example, 2 models provide a completion and a third model evaluates the completions and compare those to the example_output and rubric, and determines which model performs better

{ 
  "prompt": "System: You are a helpful assistant.\n\nHuman: What is the capital of France? please provide other contextual information about it\n\nAssistant:", 
  "example_output": "The capital of France is Paris, located in the north-central part of the country. It is the most populous city in France and one of the world's major global cities.",
  "rubric": "The response should include the following information:\n- The name of the capital city (Paris)\n- The location of Paris within France\n- A brief description of Paris' significance" 
}
