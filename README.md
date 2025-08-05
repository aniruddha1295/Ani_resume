flowchart TD
    %% Main Process Flow with Simple Explanations
    Start([Start]) --> Join["1. MSME Joins SahyogLogistics
    (Simple registration via app/website)"]
    
    Join --> InputData["2. Share Delivery Information
    (Automatic from business software or manual entry)"]
    
    InputData --> FindMatches["3. System Finds Sharing Opportunities
    (Matching algorithm identifies complementary needs)"]
    
    FindMatches --> Propose["4. Collaboration Proposals
    (MSMEs receive simple sharing suggestions)"]
    
    Propose --> Decision{"5. Accept
    Proposal?"}
    
    Decision -->|"Yes"| CreatePlan["6. Create Shared Delivery Plan
    (System optimizes routes and schedules)"]
    
    Decision -->|"No"| Solo["6A. Solo Delivery
    (Traditional delivery without sharing)"]
    
    CreatePlan --> Execute["7. Execute Shared Delivery
    (Drivers follow optimized shared routes)"]
    
    Execute --> Track["8. Track Deliveries
    (Real-time updates for all parties)"]
    
    Track --> Complete["9. Delivery Completion
    (System confirms successful deliveries)"]
    
    Complete --> Payments["10. Automatic Payments
    (Fair cost-sharing based on usage)"]
    
    Payments --> Feedback["11. Feedback & Ratings
    (MSMEs rate experience)"]
    
    Feedback --> Improve["12. Continuous Improvement
    (System learns and gets better)"]
    
    Improve --> |"Next Day"| FindMatches
    
    Solo --> Track
    
    %% Benefits Highlighted
    Improve -.-> |"Results"| Benefits["Business Benefits:
    • 30-40% lower delivery costs
    • Reduced empty trips
    • Less traffic & pollution
    • Higher vehicle utilization"]
    
