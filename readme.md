
# Sublime WordPress i18n
Simple sublime package to make WordPress theme/plugin translation ready.

![Sublime WordPress I18N](https://maheshwaghmare.files.wordpress.com/2018/01/2018-01-13_16-46-081.gif)

### Snippets:

<table>
	<tr>
		<th>Snippet</th>
		<th>Output</th>
	</tr>
	<tr>
		<td>wpi18__</td>
		<td>__( 'Hello.', 'text-domain' );</td>
	</tr>
	<tr>
		<td>wpi18_e</td>
		<td>_e( 'Hello.', 'text-domain' );</td>
	</tr>
	<tr>
		<td>wpi18_n</td>
		<td>_n( '%s Comment', '%s Comments', get_comments_number(), 'text-domain' );</td>
	</tr>
	<tr>
		<td>wpi18_x</td>
		<td>_x( 'Hello.', 'Description of translation string.', 'text-domain' );</td>
	</tr>
	<tr>
		<td>wpi18_nx</td>
		<td>_nx( '%s Comment', '%s Comments', get_comments_number(), 'Description of translation string.', 'text-domain' );</td>
	</tr>
	<tr>
		<td>wpi18_sprintf__</td>
		<td>sprintf( __( 'You have chosen the %1$s theme.', 'text-domain' ), $color );</td>
	</tr>
	<tr>
		<td>wpi18_printf__</td>
		<td>printf( __( 'You have chosen the %1$s theme.', 'text-domain' ), $color );</td>
	</tr>
</table>