# jekyll-pagination

Jekyll plugin to extend the pagination generator.

## VERSION

This documentation refers to jekyll-pagination version 0.0.4


## DESCRIPTION

Jekyll plugin to extend the pagination generator.

Add the following to your ```_plugins/ext.rb``` file:

```ruby
require 'jekyll/pagination'
```

Then set ```+paginate_file+``` or ```+paginate_files+``` in your ```_config.yml``` like:

```yaml
paginate: 10
paginate_file: blog.html
```

or

```yaml
paginate: 10
paginate_files:
- blog.html
- projects.html
```

The default is to paginate the ```index.html``` file.


## LINKS

<table>
  <tbody>
    <tr>
      <td>Documentation</td>
      <td><a href="http://blackwinter.github.com/jekyll-pagination" alt="Documentation" title="Documentation">http://blackwinter.github.com/jekyll-pagination</a></td>
    </tr>
    <tr>
      <td>Source code</td>
      <td><a href="http://github.com/blackwinter/jekyll-pagination" alt="Source code" title="Source code">http://github.com/blackwinter/jekyll-pagination</a></td>
    </tr>
    <tr>
      <td>RubyGem</td>
      <td><a href="http://rubygems.org/gems/jekyll-pagination" alt="RubyGem" title="RubyGem">http://rubygems.org/gems/jekyll-pagination</a></td>
    </tr>
  </tbody>
</table>

## AUTHORS

* [Jens Wille](mailto:jens.wille@gmail.com)
* [Arne Eilermann](mailto:eilermann@lavabit.com)


# LICENSE AND COPYRIGHT

Copyright (C) 2010-2012 University of Cologne,
Albertus-Magnus-Platz, 50923 Cologne, Germany

Copyright (C) 2013 Jens Wille

jekyll-pagination is free software: you can redistribute it and/or modify it
under the terms of the GNU Affero General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your option)
any later version.

jekyll-pagination is distributed in the hope that it will be useful, but
__WITHOUT ANY WARRANTY__; without even the implied warranty of __MERCHANTABILITY__ or
__FITNESS FOR A PARTICULAR PURPOSE__. See the GNU Affero General Public License
for more details.

You should have received a copy of the GNU Affero General Public License along
with jekyll-pagination. If not, see [GNU Licenses](http://www.gnu.org/licenses/)
