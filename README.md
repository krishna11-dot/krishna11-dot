Hi there, I'm Krishna 👋
Who am I?
I'm an AI and machine learning engineer with an MSc in Artificial Intelligence from the University of Aberdeen. Currently working as a Data Science Intern at Vector Cube building production multi-agent systems and time series forecasting pipelines, plus doing my AI Residency at Apziva where I've shipped projects spanning reinforcement learning, NLP, and computer vision.
Recently built a supply chain climate risk assessment system using LangGraph with hierarchical multi-agent architecture. Four specialist agents (Physical Hazards, Transition Risks, Regulatory, Supply Chain) process real-time news achieving ninety-seven percent risk identification. The interesting engineering challenge was reducing token consumption by ninety-two percent through smart context limiting while maintaining accuracy. Deployed as a CLI application running twenty-four seven using tmux because sometimes the simplest deployment is the best deployment.
Also shipped a stock market trading signal system using ARIMA forecasting with walk-forward validation. The system generates seven hundred sixty daily signals across three stocks with fifty-five percent direction accuracy, which sounds modest until you realize beating fifty percent consistently is genuinely hard with statistical methods. Built FastAPI backend serving predictions with sub-one-hundred-millisecond response times because traders don't wait around. Automated the entire pipeline with APScheduler triggering data fetch, model retraining, and PostgreSQL persistence every morning.
Working on a Sales CRM optimization system using Q-Learning reinforcement learning. The goal is improving customer acquisition rates from the baseline zero point four four percent, and early results show three point four times improvement reaching one point five percent. The interesting part is handling the sixty-five to one class imbalance where most customers don't subscribe, so the agent had to learn from extremely sparse positive signals. Tabular Q-Learning with sixteen-dimensional state space converging to one thousand seven hundred thirty-eight states after one hundred thousand episodes.
Earlier this year built a production-ready system detecting AI-generated fake audio. Got hands-on with NeuTTS Air for generating synthetic training samples and trained CNN-AASIST ensemble on GPU achieving ninety-eight percent F1-score. There's something satisfying about building the voice cloning system that generates the fake audio, then building the detection system that catches it. Triple-layer verification combining CNN, AASIST, and watermarking because defense in depth matters.
Also experimented with voice cloning plus Wav2Lip for lip syncing in videos. Works beautifully for front-facing shots, but I discovered Wav2Lip struggles with profile or sideways faces where the lip sync ends up in the wrong position. The model was clearly trained on frontal face datasets, which is a great reminder that computer vision models have their assumptions baked in. Now whenever I see a paper claim "state of the art results," my first question is "on what specific dataset under what specific conditions?"
🚀 What I'm passionate about
I'm fascinated by the potential of AI to solve real-world problems. My journey so far has taken me through:
Building ML systems that actually work in production. There's a massive gap between "it works on my laptop" and "it works reliably serving real users handling edge cases gracefully." I'm obsessed with bridging that gap because that's where the real engineering happens.
Exploring agentic AI and multi-agent systems. Autonomous agents that can actually accomplish complex tasks by breaking them down, using tools, and self-correcting. LangGraph has been my framework of choice for building these systems with hierarchical supervisor patterns and reflection.
Time series forecasting and sequential data. There's something elegant about ARIMA models that capture trend and seasonality through pure statistics. Sure, neural networks get all the hype, but sometimes autoregressive integrated moving averages are exactly what you need.
Reinforcement learning for decision optimization. Teaching agents to learn optimal policies through trial and error interaction with environments. Q-Learning achieving three point four times improvement on real business metrics proves these algorithms work beyond toy problems.
Computer vision applications. Teaching computers to see and understand visual information. From detecting page flips in document scanners to identifying fake audio through spectrogram analysis, vision-based approaches keep surprising me with their effectiveness.
Making LLMs actually useful. Conversational AI is cool, but LLMs integrated into multi-agent workflows with proper guardrails and validation? That's where the real business value lives.
🔍 What I'm looking for
Seeking full-time roles in ML Engineering, AI Engineering, Data Science, or Agentic AI Development where I can build production systems that solve real problems. Particularly interested in companies working on multi-agent systems, time series applications, or production ML infrastructure.
🌱 Current learning journey
Deep diving into multi-agent architectures. Hierarchical supervisor patterns, tool orchestration, state management, reflection patterns. LangGraph has become my go-to framework for building these systems.
Reinforcement learning algorithms. Q-Learning, policy gradients, exploration versus exploitation tradeoffs. The math is beautiful when you actually implement it from scratch.
Time series forecasting techniques. ARIMA, walk-forward validation, stationarity testing. Learning that sometimes the classical statistical methods outperform fancy neural networks.
Production ML patterns. FastAPI for serving models, PostgreSQL for persistence, APScheduler for automation, tmux for deployment. The unglamorous infrastructure work that makes systems actually reliable.
Experimenting with prompt engineering. LLMs are weird and wonderful. Getting them to consistently produce structured outputs requires understanding their failure modes and building proper validation layers.
Constantly refining Python skills. PyTorch for deep learning, scikit-learn for classical ML, Pandas for data wrangling, Pydantic for validation. The ecosystem keeps growing.
📚 Current inspirations
Getting lost in Dwarkesh Patel and Lex Fridman podcasts. Random research papers that lead me down rabbit holes at two in the morning. The open-source ML community who builds incredible tools and shares knowledge freely. You're all amazing.
📚 When I'm not coding...
Playing football (still waiting for my Premier League call-up). Hiking and exploring new trails (the Aberdeenshire trails were incredible). Getting lost in thought while listening to tech and philosophy podcasts. Pondering questions like "what does AI alignment even mean?" over coffee.
Trying (and often failing) to explain what I do to my non-tech friends:
"So you teach computers to think?"
"Not exactly..."
fifteen minutes later
"So... you teach computers to think?"
"Close enough."
🤝 Let's connect!
I'm always up for interesting conversations about AI, ML engineering, or just sharing learning resources. Feel free to reach out if you're working on something cool or have advice about the field.
📧 krishnanair041@gmail.com
🔗 LinkedIn
"The measure of intelligence is the ability to change." — Albert Einstein
