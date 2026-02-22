# Carter Nadain - Computer Science ePortfolio

**Full-Stack Developer | SNHU Computer Science Graduate**

React • Next.js • MongoDB • Node.js • SQL

---

##  Professional Self-Assessment

As a Computer Science student at Southern New Hampshire University, my growth has gone far beyond just learning syntax or getting code to run. Over time I have developed the ability to think more like an engineer instead of just a programmer. This ePortfolio reflects that shift. It shows how I design systems that are maintainable, analyze performance intentionally, structure databases with purpose, and approach development with a security first mindset.

When I first started, my mindset was simple. I wanted to make things work. If the feature functioned, I felt successful. Through coursework, full stack projects, and especially this capstone, I learned that professional development is about building systems that scale, evolve, and make sense to other developers. Clean architecture, separation of concerns, and thoughtful technical decisions matter just as much as working code. The artifacts in this portfolio show that transition clearly, from functional solutions to engineered systems.

### Collaborating in Team Environments

One of the biggest lessons I have learned is that software is never built alone. Between academic team projects and real world work using React, Next.js, and SQL, I have seen how important communication and version control are. Git and GitHub are not just tools I use. They are part of how I think about collaboration. Clear commit messages, structured branches, and readable pull requests keep teams aligned and prevent confusion. As someone working toward becoming a stronger full stack engineer, I focus on writing code that other developers can understand and build on.

###  Communicating with Stakeholders

Strong communication also means explaining technical ideas in a way that connects to business value. Throughout this capstone, I practiced breaking down concepts like time complexity, indexing strategies, and service layer architecture into language that makes sense to non technical stakeholders. Instead of focusing only on implementation details, I explain what those decisions accomplish for the business, such as improving performance, enabling analytics, or reducing long term maintenance costs.

###  Data Structures and Algorithms

My growth in data structures and algorithms is another area that stands out. Earlier in my program I understood algorithms at a surface level. Now I think more critically about scalability and tradeoffs. Implementing search, filter, and sorting functionality with documented time complexity forced me to consider how systems behave as data grows. I learned to evaluate performance, justify my choices, and understand how data structures impact efficiency.

###  Software Engineering and Databases

Across software engineering, algorithms, and database enhancements, this portfolio demonstrates how I approach systems as a whole. I refactored tightly coupled components into cleaner architectures with clear separation of concerns and centralized error handling. I implemented structured data models and layered logic to support flexible user functionality. I optimized database performance through indexing and enforced data integrity through schema validation.

###  Security Mindset

Security has also become a consistent priority in my development process. I implemented validation at multiple layers to prevent malformed data and protect system integrity. By validating on the frontend, within the API, and at the database schema level, I applied a defense in depth approach that reduces risk and strengthens reliability.

###  Professional Goals

Completing this capstone has reinforced my direction as a developer. I am not focused on simply knowing frameworks. I am focused on understanding architecture, performance, scalability, and long term maintainability. As I continue working with modern stacks such as MERN and Next.js, I aim to deepen my backend knowledge while continuing to strengthen frontend expertise.

---

##  Code Review

**[Watch Code Review Video]()**

In this code review, I walk through the original pizza ordering application, identify areas for improvement in software design, algorithms, and database structure, and outline my enhancement plan across all three categories.

**Key Topics Covered:**
- Existing functionality walkthrough
- Code analysis: structure, efficiency, security
- Planned enhancements for each category
- Alignment with course outcomes

---

## Project Artifacts

### Enhancement One: Software Design & Engineering

**[View Code Repository](https://github.com/carternadain/pizza-app)**

#### Overview
Refactored a full-stack pizza ordering application to improve architecture, maintainability, and user experience through professional software engineering practices.

#### Key Improvements
- **Service Layer Architecture**: Created `pizzaService.js` to centralize all API calls, separating network logic from UI components
- **Component Refactoring**: Extracted `PizzaCard` component following single responsibility principle
- **Error Handling**: Implemented centralized error handling with user-facing messages
- **Input Validation**: Added validation at service layer to prevent invalid data
- **Responsive Design**: Fixed mobile navigation with hamburger menu and CSS media queries

#### Technical Skills Demonstrated
- Separation of concerns
- Modular architecture
- Defensive programming
- Mobile-first responsive design
- Professional error handling

#### Time Complexity Impact
- Improved maintainability from O(n) scattered changes to O(1) centralized updates
- Reduced debugging time through clear architectural boundaries

**[Read Full Narrative](./narratives/enhancement-one.md)**

---

### Enhancement Two: Algorithms & Data Structures

**[View Code Repository](https://github.com/carternadain/pizza-app)**

#### Overview
Implemented search, filter, and sort algorithms with proper data structure design to enable efficient data manipulation and improve application usability.

#### Key Improvements
- **Data Models**: Created `Pizza` and `Topping` classes with encapsulated methods (`calculateTotalPrice()`, `hasTopping()`, `getToppingDetails()`)
- **Search Algorithm**: Linear search with O(n) complexity for case-insensitive partial matching
- **Filter Algorithm**: Topping-based filtering with O(n×m) complexity
- **Sort Algorithms**: Implemented O(n log n) sorting by name (A-Z, Z-A) and topping count
- **Multi-Criteria Search**: Composite algorithm combining search, filter, and sort operations

#### Technical Skills Demonstrated
- Algorithm design and implementation
- Time complexity analysis (Big O notation)
- Object-oriented design principles
- Functional programming (non-mutating operations)
- Performance optimization

#### Performance Metrics
```
Linear Search:     O(n)   - Scales linearly with pizza count
Filter by Topping: O(n×m) - Depends on pizzas and toppings per pizza
Sorting:           O(n log n) - Efficient comparison-based sorting
```

**[Read Full Narrative](./narratives/enhancement-two.md)**

---

### Enhancement Three: Databases

**[View Code Repository](https://github.com/carternadain/pizza-app)**

#### Overview
Optimized MongoDB database through strategic indexing, schema validation, and aggregation pipelines to improve performance, data integrity, and analytics capabilities.

#### Key Improvements
- **Strategic Indexing**: 
  - Single-field indexes on `name` for O(log n) search
  - Compound indexes on `{name, popularity}` for combined operations
  - Text indexes for full-text search capability
  - Array indexes on `toppings` for efficient filtering

- **Schema Validation**:
  - Regex patterns preventing injection attacks
  - Price and quantity bounds checking
  - Referential integrity for topping references
  - Category enums for data consistency

- **Aggregation Pipelines**:
  - Pizza statistics (total, avg toppings, min/max)
  - Topping usage analysis with `$unwind`, `$group`, `$lookup`
  - Popular pizza rankings

- **Analytics Dashboard**: React component visualizing database insights

#### Technical Skills Demonstrated
- Database performance optimization
- Schema design and validation
- Advanced MongoDB aggregation
- Defense-in-depth security
- Full-stack data visualization

#### Performance Impact
```
Before Indexing:  O(n) collection scans
After Indexing:   O(log n) indexed lookups
Improvement:      ~100x faster on 10,000+ records
```

**[Read Full Narrative](./narratives/enhancement-three.md)**

---

##  Links & Resources

- **GitHub Repository**: [pizza-app](https://github.com/carternadain/pizza-app)
- **LinkedIn**: [Carter Nadain](https://www.linkedin.com/in/carternadain)
- **Email**: carter.nadain@snhu.edu

---

##  Technologies Used

**Frontend:**
- React 18
- Vite
- Tailwind CSS (via CDN)
- Axios
- React Router

**Backend:**
- Node.js
- Express
- MongoDB with Mongoose
- RESTful API design

**DevOps:**
- Git & GitHub
- Heroku deployment
- MongoDB Atlas

**Tools:**
- VS Code
- Postman (API testing)
- Chrome DevTools

---

##  Course Outcomes Achieved

 **Collaborative Environments**: Demonstrated through clear documentation, version control practices, and code designed for team maintainability

 **Professional Communication**: Developed technical narratives explaining design decisions, tradeoffs, and business value

 **Algorithmic Principles**: Implemented and analyzed search, filter, and sort algorithms with documented time complexity

 **Software Engineering**: Applied service layer architecture, component design patterns, and error handling strategies

 **Security Mindset**: Implemented multi-layer validation, schema enforcement, and defensive programming practices

---

##  Academic Journey

This ePortfolio represents the culmination of my Computer Science degree at Southern New Hampshire University. Through this capstone project, I transformed a basic CRUD application into a professionally-engineered system demonstrating:

- Thoughtful architectural design
- Performance-conscious algorithm implementation
- Optimized database structures
- Security-first development practices
- Clear technical communication

The progression from Enhancement One through Enhancement Three shows my growth from writing functional code to engineering maintainable, scalable, and secure systems.

---

##  Contact

**Carter Nadain**  
Computer Science Graduate | Full-Stack Developer  
 carter.nadain@snhu.edu  
[LinkedIn](https://www.linkedin.com/in/carternadain)  
 [GitHub](https://github.com/carternadain)

---

*Last Updated: February 2026*