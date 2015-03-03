# Blade templating snippets

Laravel 5 blade snippets! useful snippets for the blade templating engine.

Converted from [blade-snippets for sublime](https://github.com/dev4dev/blade-snippets)
using the [sublime to atom](https://github.com/james2doyle/sublime-to-atom-snippets) script.

##Avalable snippets

| Shortcut  | Result |
|-----------|--------|
| ext		| @extends('`name`') |
| lay		| @layout('`name`')  |
| sec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @endsection    |
| secy		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @yield_section |
| yl		| @yield('`section`', '`default`') |
| lsec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @show |
| par		| @parent	|
| !!		| {!! $`var` !!}	|
| inc		| @include('`view.name`', `['some' => 'data']`)  |
| if		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @endif   |
| ife		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @else <br /> **{{-- expr --\}\}** <br /> @endif  |
| foreach	| @foreach(`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforeach  |
| fore		| @forelse (`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforelse  |
| for		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /> **{{-- expr --\}\}** <br /> @endfor  |
| each		| @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| trans		| {!! trans('`language.line`') !!}	|
| route		| {!! route('`name`') !!}	|
| asset		| {!! asset('`path`') !!}	|
| action	| {!! link_to_action('`Controller@method`') !!}	|
| while		| @while (`condition`) <br /> **{{-- expr --\}\}** <br /> @endwhile  |
| unless	| @unless (`condition`) <br /> **{{-- expr --\}\}** <br /> @endunless  |
| choice	| @choice('`language.line`', $`number`)  |
| comment	| {{-- `comment` --}}	|
| lang		| @lang('`language.line`', `['variable => 'replacement']`)  |


##Disclaimer

Feel free to contribute!

As of today, i am a complete noob at making atom packages, if there is any error,
suggestion, improvement, etc, to point or make, feel free to do so.
