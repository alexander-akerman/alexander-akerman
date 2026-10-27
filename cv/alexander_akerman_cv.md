# Alexander Akerman

Software Engineer | AI Platforms | Computer Vision | Backend Systems

[alexakerman@outlook.com](mailto:alexakerman@outlook.com) | [linkedin.com/in/akermanalex](https://www.linkedin.com/in/akermanalex/) | [github.com/alexander-akerman](https://github.com/alexander-akerman)

## Professional Summary

Software engineer with 15 years of experience, serving as lead engineer for multiple production backend, AI, and media-processing systems. Combines architectural decision-making and hands-on implementation with production operations and cross-team delivery.

## Professional Experience

### eBay | 2011-Present

#### Software Engineer | AI Platforms and Computer Vision | 2019-Present

##### AI Platforms and Production Services

- Supported risk and compliance requirements for expanding live-commerce access to all sellers by identifying items without seller-provided listing details. Combined video frames, transcripts, and auction change data capture (CDC) events using Flink, Kafka, and Gemini Live API.
- Enabled external eBay developers to get answers grounded in official documentation by designing and implementing the retrieval-augmented generation (RAG) component of a production support agent, including vector storage, query embedding, and retrieval.
- Designed and built a production pipeline that processes approximately 2,400 images per second at peak and publishes embeddings downstream, enabling compliance teams to identify prohibited, restricted, and counterfeit items using their own reference database. Owned deployment and on-call operations.
- Built a Spring Boot starter and tracing tools for an AI agent framework adopted by multiple production agents.

##### Computer Vision and Model Serving

- Reduced delays before newly listed trading cards became available for image matching by leading matching development and automating index generation.
- Integrated machine learning models into production serving infrastructure, porting Python preprocessing and post-processing to Java.
- Integrated SIFT and FFmpeg libraries with Java through JNI for production image matching, media inspection, and frame extraction.

##### Media Processing and Moderation

- Saved approximately $170,000 annually by leading migration from an external video-moderation vendor to an in-house pipeline. Handles approximately 20,000 videos per day, with capacity for approximately 80,000 per day, and blocks several dozen inappropriate videos daily.
- Flagged images unsuitable for advertising and detected off-platform buyer redirection in member messages through a production image classification and OCR pipeline handling approximately 4,500 image uploads per second. Built with Kotlin, Spring Boot, Kafka, and OpenCV.

#### Software Engineer | 2014-2019

Metadata Tools

- Developed and maintained a full-stack metadata application for internal users using React, Java, Spring, and Neo4j.


#### Software Engineer | 2011-2014

Data Ingestion and Processing

- Maintained production-critical vendor data ingestion and ETL (extract, transform, load) infrastructure using Perl, Java, and Linux.

## Technical Skills

- **Languages:** Java, Kotlin, Python, JavaScript, Perl
- **Backend and Infrastructure:** Spring Boot, Kafka, Flink, REST APIs, Docker, Kubernetes, Avro, Amazon S3
- **AI and Computer Vision:** NVIDIA Triton Inference Server, OpenCV, OCR, FFmpeg, SIFT, Gemini Live API
- **Platforms and Tools:** Java Native Interface (JNI), MongoDB, Neo4j, React, Linux, Maven, CMake, Micrometer
