# Blade templating snippets for Atom

Laravel 5 blade snippets! useful snippets for the Blade Templating Engine to use in Atom.

Converted from [blade-snippets for sublime](https://github.com/dev4dev/blade-snippets)
using the [sublime to atom](https://github.com/james2doyle/sublime-to-atom-snippets) script.

## Usage

These snippets will trigger only in `*.blade.php` files.

Type any snippet and hit TAB to receive incredible results!.

echo + TAB = {{ `$var` }}

Checkout the [Available blade snippets.](#available-snippets)

I recommend [this Blade language Package for Atom](https://atom.io/packages/language-blade) to be able to take full advantage of the Blade Templating Engine in this amazing editor.

## Available snippets

| Shortcut  | Result |
|-----------|--------|
| **!!**	_or_ **uecho** _or_	**uprint** | {!! `$var` !!}	|
| **}}** _or_ **echo** _or_	**print**	| {{ `$var` }} |
| **action**	| {!! link_to_action('`Controller@method`') !!}	|
| **asset**		| {!! asset('`path`') !!}	|
| **choice**	| @choice('`language.line`', $`number`)  |
| **comment** _or_ **//**	| {{-- `comment` --}}	|
| **each** | @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| **ext**	_or_ **extends** | @extends('`name`')	|
| **fea** _or_ **foreach** | @foreach(`$array` as `$element`) <br /><br /> @endforeach |
| **fel** _or_ **forelse**| @forelse (`$array` as `$element`) <br /><br /> @endforelse  |
| **for**		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /><br /> @endfor  |
| **if**	| @if (`condition`) <br /><br /> @endif   |
| **ife**	| @if (`condition`) <br /><br /> @else <br /><br /> @endif  |
| **inc**	_or_ **include** | @include('`view.name`', `['some' => 'data']`)  |
| **par**	_or_ **parent**	| @parent	|
| **route**		| {!! route('`name`') !!}	|
| **sec**	_or_ **section** | @section('`name`') <br /><br /> @endsection |
| **sshow**	_or_ **secs** | @section('`name`') <br /><br /> @show |
| **trans**		| {!! trans('`language.line`') !!}	|
| **un** _or_ **unless** | @unless (`condition`) <br /><br /> @endunless  |
| **while**		| @while (`condition`) <br /><br /> @endwhile  |
| **yl** _or_ **yield**	| @yield('`section`') |


## Disclaimer

Feel free to contribute!

As of today, i am a complete noob at making atom packages, if there is any error,
suggestion, improvement, etc, to point or make, feel free to do so.
