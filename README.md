Hydr8
===

Introduction
------------
Hyrd8 is Ruby on Rails project designed to facilitate the mapping and importing of complex data. It provides a flexible and extensive framework for handling diverse data types and associations within a Ruby on Rails application.

Key Features
------------
    Flexible Mapping: Hydr8 supports the mapping of various data types, attributes, and associations, allowing developers to define custom mappings based on specific requirements.

    Association Handling: Different types of associations, including belongs_to, has_many, and polymorphic associations, are supported. The engine can build, edit, and manage associations during the import process.

    Error Handling: The engine incorporates a comprehensive error handling mechanism, allowing for the detection and reporting of errors during the mapping and importing process.

    Validity Checks: The engine performs validity checks on attributes and values, ensuring that the imported data meets the expected criteria. It includes checks for frozen records, boolean values, and enumerated types.

    Recursion: The engine supports recursive mapping by calling itself when dealing with associated models. This allows for the seamless handling of nested data structures.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/hydr8.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
