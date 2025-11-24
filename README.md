# Campus Course & Records Manager (CCRM)

## Project Overview
A console-based Java SE application to manage students, courses, enrollments, grades, transcripts, and file operations for an academic institute. Demonstrates OOP, Java SE features, modern I/O, Streams, Date/Time API, design patterns, and robust exception handling.

## How to Run
- Requires JDK 17+ (or latest Java SE)
- Compile: `javac edu/ccrm/cli/Main.java`
- Run: `java edu.ccrm.cli.Main`

## Evolution of Java (Timeline)
- 1995: Java 1.0 released
- 1998: Java 2 (J2SE, J2EE, J2ME)
- 2004: Java 5 (Generics, Enums)
- 2014: Java 8 (Lambdas, Streams)
- 2017: Java 9+ (Modules, JShell)
- 2021: Java 17 (LTS)

## Java ME vs SE vs EE
| Edition | Purpose | Example |
|--------|---------|--------|
| Java ME | Embedded/mobile | Smart cards, IoT |
| Java SE | Desktop/server | CLI, GUI apps |
| Java EE | Enterprise/web | Web servers, APIs |

## Java Architecture
- **JDK**: Java Development Kit (compiler, tools)
- **JRE**: Java Runtime Environment (JVM + libraries)
- **JVM**: Java Virtual Machine (executes bytecode)
- JDK ⟶ JRE ⟶ JVM

## Install Java on Windows
1. Download JDK from [Oracle](https://www.oracle.com/java/technologies/downloads/)
2. Run installer, set JAVA_HOME
3. Add to PATH
4. Verify: `java -version`

## Eclipse Setup
1. Open Eclipse IDE
2. File → New → Java Project
3. Add source folders/packages
4. Run Main class

## Mapping Table
| Syllabus Topic | File/Class/Method |
|---------------|-------------------|
| Encapsulation | domain/Student.java |
| Inheritance | domain/Person.java, Student.java |
| Abstraction | domain/Person.java |
| Polymorphism | TranscriptService.java, Transcript.java |
| Exception Handling | util/DuplicateEnrollmentException.java |
| Streams | service/CourseServiceImpl.java |
| NIO.2 | io/ImportExportService.java |
| Date/Time API | domain/Enrollment.java |
| Singleton | config/AppConfig.java |
| Builder | domain/Course.java (static nested Builder) |
| Enums | domain/Semester.java, Grade.java |
| Lambdas | util/Comparators.java |
| Recursion | util/BackupUtils.java |
| CLI | cli/CLI.java |

## Enabling Assertions
- Add `-ea` to JVM args: `java -ea edu.ccrm.cli.Main`

## Sample Commands & Data
- See USAGE.md or below for sample menu operations and CSVs in `test-data/`

## Screenshots
- Add screenshots of JDK install, Eclipse setup, program running, exports/backups

## Acknowledgements
- Cite any references here

## Optional Demo Video
- Add YouTube/Drive link here
