I want to build a data integration and AI analysis platform that connects Notion, Supabase, and AI services using a clean architecture approach. The primary goal is to create a system that's highly maintainable and easily refactorable, with a strong emphasis on separation of concerns and the single responsibility principle.

The first major component involves interaction with the Notion API. I need a flexible system to fetch data from Notion databases with various filtering capabilities. This includes retrieving specific columns, rows, or date ranges, and handling the data in a way that's easily manipulatable. The system should be able to both read from and write to Notion, using page IDs as unique identifiers for data manipulation.

The second component focuses on Supabase integration. I want to establish a one-way synchronization from Notion to Supabase, ensuring that my Notion data is reliably backed up and accessible through Supabase. This requires functionality to create and manage tables in Supabase that mirror my Notion databases, along with utility functions for database interactions.

The third component involves AI integration, specifically with Anthropic and OpenAI services. I need to manage system prompts and user prompts effectively, process data through these AI services, and handle their responses. The AI component will analyze data from Notion and generate outputs that can be sent back to either Notion or Supabase.

The system needs robust data flow management: from Notion to Supabase for synchronization, from Notion to AI services for analysis, and from AI services back to either Notion or Supabase for storage. This requires careful consideration of data structures, API interactions, and error handling to ensure smooth operation across all components.
