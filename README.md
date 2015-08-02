#Blade templating snippets for Atom

Laravel 5 blade snippets! useful snippets for the Blade Templating Engine to use in Atom.

Converted from [blade-snippets for sublime](https://github.com/dev4dev/blade-snippets)
using the [sublime to atom](https://github.com/james2doyle/sublime-to-atom-snippets) script.

##Usage

These snippets will trigger only in `*.blade.php` files.

Type any snippet and hit TAB to receive incredible results!.

echo + TAB = {{ `$var` }}

Checkout the [Available blade snippets.](#available-snippets)

I recommend [this Blade language Package for Atom](https://atom.io/packages/language-blade) to be able to take full advantage of the Blade Templating Engine in this amazing editor.

##Available snippets

| Shortcut  | Result |
|-----------|--------|
| **}}** _or_ **echo** _or_	**print**	| {{ `$var` }} |
| **!!**	_or_ **uecho** _or_	**uprint** | {!! `$var` !!}	|
| **sec**	_or_ **section** | @section('`name`') <br /><br /> @endsection |
| **sshow**	_or_ **secs** | @section('`name`') <br /><br /> @show |
| **inc**	_or_ **include** | @include('`view.name`', `['some' => 'data']`)  |
| **ext**	_or_ **extends** | @extends('`name`')	|
| **yl** _or_ **yield**	| @yield('`section`') |
| **par**	_or_ **parent**	| @parent	|
| **if**	| @if (`condition`) <br /><br /> @endif   |
| **ife**	| @if (`condition`) <br /><br /> @else <br /><br /> @endif  |
| **for**		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /><br /> @endfor  |
| **while**		| @while (`condition`) <br /><br /> @endwhile  |
| **un** _or_ **unless** | @unless (`condition`) <br /><br /> @endunless  |
| **fea** _or_ **foreach** | @foreach(`$array` as `$element`) <br /><br /> @endforeach |
| **fel** _or_ **forelse**| @forelse (`$array` as `$element`) <br /><br /> @endforelse  |
| **each** | @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| **trans**		| {!! trans('`language.line`') !!}	|
| **route**		| {!! route('`name`') !!}	|
| **asset**		| {!! asset('`path`') !!}	|
| **action**	| {!! link_to_action('`Controller@method`') !!}	|
| **choice**	| @choice('`language.line`', $`number`)  |
| **comment** _or_ **//**	| {{-- `comment` --}}	|


##Disclaimer

Feel free to contribute!

As of today, i am a complete noob at making atom packages, if there is any error,
suggestion, improvement, etc, to point or make, feel free to do so.
