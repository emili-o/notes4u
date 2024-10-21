---
{"dg-publish":true,"permalink":"/note/s3-objects/","tags":["note"]}
---

# What are “objects” in [[S3 - Amazon Simple Storage Service\|S3]]?

> [!info] S3 utilizes an object-based model
> The organization of files in Amazon S3 differs from traditional file systems, which typically rely on folders and a hierarchical structure. In S3, the storage structure is flat, and everything is managed by keys. 
>
This key-based system offers more flexibility for different applications, allowing for a more adaptable and scalable approach to file storage and management.

An object is a single piece of data stored in the service. Every object consists of:
1. Data
2. Metadata
3. Unique identifier

Objects are stored in “buckets”, and the combination of the bucket name and unique identifier forms the unique URL for each object.