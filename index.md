---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

```ruby
require('developer_lookup')

module RubyOnRails
  class Developer
    def initialize(name, experience)
      @name = name
      @experience = experience
    end

    def details
      @details ||= DeveloperLookup.get_details(self)
    end
  end
end
```

```ruby
irb> me = RubyOnRails::Developer.new('Fabio Papa', 16.years)
irb> puts me.details
{
  loves_ruby: true,
  loves_rails: true,
  personality: 5/5,
  independent_work: 5/5,
  team_work: 5/5
}
irb>
```
